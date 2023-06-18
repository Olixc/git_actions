# Learn GitHub Actions

This repository contains a GitHub Actions workflow named "learn-github-actions" that demonstrates how to use GitHub Actions to check the version of the "bats" package. The workflow is triggered on a push event.

## Workflow Description

The workflow consists of a single job named "check-bats-version" that runs on the latest version of Ubuntu. The job performs the following steps:

1. Checks out the repository's code in the runner's workspace.
2. Sets up the Node.js environment with Node.js version 14.
3. Installs the "bats" package globally using npm.
4. Executes the Bats test suite and prints verbose output and a summary of the test results.

## Usage

To use this workflow, follow these steps:

1. Create a new file named `.github/workflows/learn-github-actions.yml` in the root of your GitHub repository.
2. Copy the provided YAML code into the `learn-github-actions.yml` file.
3. Commit and push the changes to your repository.

After these steps, the workflow will be automatically triggered whenever you push changes to your repository. You can monitor the workflow runs in the "Actions" tab of your repository on GitHub.

**Note**: Please ensure that you have a compatible version of Node.js installed on your local machine if you plan to execute this workflow locally.

For more information on GitHub Actions and how to customize workflows, refer to the [official documentation](https://docs.github.com/en/actions).
