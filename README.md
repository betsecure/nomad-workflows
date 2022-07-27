# Nomad Workflows

Reusable GitHub Actions workflows for the Nomad project.

These workflows are not general purpose; they are designed solely for use by the
BetSecure organization. They may change at any time and without warning.

## Usage

The workflow files in the [`usage`](./usage) directory demonstrate how to
reference these workflows from other projects.

They represent the common usage and can generally be copied directly into your project's `.github/workflow` directory without modification.

## Why is this repository public?

GitHub Actions does not currently support calling reusable workflows from
private repositories.

> Care must be taken to avoid embedding any secrets, domain names, or other
> sensitive information.

Use [inputs and secrets] to pass any non-public information into these
workflows.

[inputs and secrets]: https://docs.github.com/en/actions/using-workflows/reusing-workflows#using-inputs-and-secrets-in-a-reusable-workflow
