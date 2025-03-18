# abinit_actions

This repository uses GitHub Actions to test an external repository periodically 
and display the test results as a badge.

## How It Works

1. Checks out this repository.
2. Checks out the external repository to test.
3. Sets up Python and installs dependencies.
4. Runs the tests using `pytest`.

## Status

1. Replace `owner/repository-to-test` in `.github/workflows/test-other-repo.yml` with the actual repository you want to test.
2. Modify the `python-version` in the workflow if needed.
3. Commit and push the changes to trigger the first run

![configure and compilation](https://github.com/abinit/abinit_actions/actions/workflows/download_abinit_and_make/badge.svg)













