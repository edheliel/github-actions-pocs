## github-actions-pocs

Those are POC Github Actions that implement possible ways to exploit Github Actions or exfilitrate data.
The Author is not responsible for it's missuse.

## Running Github Actions Locally

Recommended way of testing actions via containers [nektos/act](https://github.com/nektos/act)

Run all workflows:

```
act pull_request --verbose --secret-file ./.secrets --workflows ./.github/workflows/ --reuse
```

Test a specific job:

```
act pull_request --verbose --secret-file ./.secrets --job <job-name> --reuse
```
