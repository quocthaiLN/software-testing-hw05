# Software Testing Homework

## Structure
- There are 6 homeworks
- Each homework is placed in `hw<n>`, from `hw01` to `hw06` contains:
    - `2026.HW<n>.<homeword-name>.md`: contains requirments of the homework
    - `submission/`: contains the submission of the homework
    - `requirements_list.md`: requirement checklist derived from the original assignment, with source references, deliverables, and acceptance criteria.
    - `PROGRESS.md`: execution status, verification evidence, blockers, and next actions linked to the requirement checklist.

## Principals
- Reading homework requirements and principals carefully: 
    - Requirements
    - Reports & PDF
    - AI Audit Report, AI Critique, Anti-AI-Cheat Constraints
    - Git logs

- Submission file name: StudentID_ExerciseID_SelfAssessedGrade.zip. The SelfAssessedGrade must be a 3-digit number ranging from 000 to 100.

- File format: markdown & pdf

- Misuse or over-reliance on online links in the submission will result in a score of zero (0) for the assignment.
- Git Usage
    - Each homework is a GitHub repository. 
    - Must use Git (GitHub / Bitbucket / GitLab) to manage the version history of their assignment files.
    - For every step within a requirement, students must create a clear and explicit Git commit message.
    - Students may work on their personal / group GitHub repositories and submit the git commit logs. Use command `git log --graph --all --stat` to extract Git commit logs.

## Software under test
- E-commerce platform: `eshop-sut/`

## Workflow

1. Read `AGENTS.md`, `PROGRESS.md`, and `requirements-list.md`.
2. Analyze my request and derive a plan for the task.
3. Track the work in `PROGRESS.md`. A session corresponds to one whole chat conversation, not a single prompt-response pair, so one session may contain multiple prompts. Use this format:

   ```markdown
   # Session Log

   ## Session 001
   - Date:
   - Goal:
   - Completed:
   - Verification run:
   - Commits:
   - Files or artifacts updated:
   - Known risk or unresolved issue:
   - Next best step:
   ```

4. Log each interaction in `AI-Report-Audit.md` with exactly three components:
   - Date and time
   - User prompt
   - AI output
5. Update the relevant documents (`PROGRESS.md` and `requirements-list.md`).

### Requirement checklist and progress tracking

- Use `requirements_list.md` to define **what must be satisfied**, and `PROGRESS.md` to record **what has been done and verified**. Reference the same requirement IDs in progress entries, evidence, and relevant commits.
- Reconcile the checklist with the original assignment before execution and whenever requirements change. Preserve existing IDs; explicitly document additions or corrections.
- Before final packaging, review every applicable checklist item against the outputs and evidence in `PROGRESS.md`. An unchecked or unverified mandatory item prevents declaring the submission complete.

## References
- Others principals are contained in `policies.md`.
- E-commerce document: `eshop-sut/api_specification.md`, `eshop-sut/README.md`, `eshop-sut/setup_guide.md`.