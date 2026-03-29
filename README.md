# Git Project Part 2

Fork this repo to start your work.

## GitHub Actions CI

Add a GitHub Actions workflow at `.github/workflows/ci.yml` that runs on every push.

The workflow must have 3 jobs, each running a different tool (for example: a test runner, a linter, a coverage tool). You can decide which tools to use.

At least one job must use a [matrix strategy](https://docs.github.com/en/actions/writing-workflows/choosing-what-your-workflow-does/running-variations-of-jobs-in-a-workflow).

Update `requirements.txt` with anything your workflow needs.

## Grading

50 points total.

* 15 pts: Pipeline runs successfully on push
* 10 pts: Job 1
* 10 pts: Job 2
* 10 pts: Job 3
* 5 pts: Matrix strategy used correctly
