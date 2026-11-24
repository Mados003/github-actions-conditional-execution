# GitHub Actions: Conditional Execution

A small project showing conditional jobs in GitHub Actions.

## Workflow
- lint job: runs ruff.
- train job: runs only if lint passes, the branch is main, and the commit message contains [run-train]. The job is a placeholder that prints a message.

File: .github/workflows/pipeline.yaml. app.py is a tiny script used as the lint target.
