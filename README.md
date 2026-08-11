# AI Test Project

This is a dummy project used to test the AISolver CI failure detection pipeline.

## Purpose

The project intentionally contains a failing GitHub Actions workflow.

The expected pipeline is:

Developer Push
→ GitHub Actions
→ Test Failure
→ GitHub workflow_run Webhook
→ AISolver Express Backend