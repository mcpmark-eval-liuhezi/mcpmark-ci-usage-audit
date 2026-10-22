# CI Usage Notes

- The `audit.yml` workflow is triggered on demand via `workflow_dispatch`.
- Each run prints the run context (repo, run id, ref) and a short simulated release checklist.
- Billable time per run can be reviewed on the run's "Set up a job" step summary / billing report.
