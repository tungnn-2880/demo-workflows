# demo-workflows

## Workflow `demo-workflow`
[Reference](https://docs.github.com/en/actions/quickstart)

--> Useful features:
	- Create new job (workflow) to be run automatically
	- Specify job steps
	- Job step can run arbitrary shell commands from $PATH
	- Job commands can reference environment variables using Github Actions Syntax (a little different from normal shell variable reference when introduced environment scopes: `job`, `github`, `runner`, ...)
	- Very useful when listen for push events to run unit tests, and exits with 0 status to indicate success
