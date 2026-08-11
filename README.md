# AI Test Project

This is a dummy project used to test the AISolver CI failure detection pipeline.

## Purpose

The project intentionally contains a failing GitHub Actions workflow.

The expected pipeline is:

Developer Push
→ GitHub Actions
→ Test Failure
→ GitHub workflow_run Webhook
→ AISolver Express Backendtrigger webhook
webhook test
triggering CI failure
testing updated webhook router
testing updated webhook router
real github webhook test
webhook debugging
webhook debugging
real workflow webhook test
