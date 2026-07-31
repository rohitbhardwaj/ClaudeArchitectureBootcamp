# Start Here

## 1. Prepare your environment

Read `PREREQUISITES.md` and confirm:

- Git is installed;
- Java 17 or later is installed;
- Bash or a compatible shell is available;
- Claude Code is installed for the Claude Code exercises;
- Maven is installed for acts that use Maven.

## 2. Create a working branch

```bash
git checkout -b workshop/<your-name>
```

Do not work directly on the main branch.

## 3. Run the repository checks

Use `REPOSITORY_CHECKLIST.md` to verify that each act has the expected files.

## 4. Follow the acts in order

The acts deliberately build on one another:

1. understand the risk;
2. map the architecture;
3. govern the repository;
4. govern engineering changes;
5. govern model API contracts;
6. bound autonomous workflows;
7. control enterprise tools;
8. establish trust with RAG, security, evals, and observability;
9. make the production decision.

## 5. Use this method for every assignment

### Understand
Read the scenario, constraints, and required deliverables.

### Inspect
Review the relevant source, configuration, tests, evidence, or architecture.

### Baseline
Run the current tests or simulation before making changes.

### Plan
Document scope, risks, validation, and rollback.

### Execute
Make the smallest justified change or complete the architecture analysis.

### Verify
Run tests, evals, scans, checklists, or scorecards.

### Defend
Explain the decision, strongest evidence, remaining risk, owner, and rollback.

### Reflect
Read the model answer only after presenting your result.

## 6. Submission format

Create a `submission.md` inside the relevant assignment directory:

```markdown
# Assignment Submission

## Decision or result
## Baseline evidence
## Plan
## Work completed
## Verification
## Risks and controls
## Rollback or recovery
## Two-minute defense
## Reflection
```
