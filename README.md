# gh prs extension

This extension will give you the ability to conveniently list the prs a specific account was requested to do.

Handy for compiling your daily standup form.

## Installation

You can install these plugins following the [official installation instructions](https://cli.github.com/manual/gh_extension_install).

A simple way is:
- clone this repository
- `cd` to the plugin you want to install folder
- run `gh extension install .`

## Configuration

- `MECHA_GH_PRS_ORGS_EXCLUDE_FILTER`: the github organizations to exclude as a filter for PRs. It accepts comma-separated values.
- `MECHA_GH_PRS_ORGS_INCLUDE_FILTER`: the github organizations to include as a filter for PRs. It accepts comma-separated values.
- `MECHA_GH_PRS_REPO_EXCLUDE_FILTER`: the github repositories to exclude as a filter for PRs. It accepts comma-separated values.
- `MECHA_GH_PRS_REPO_INCLUDE_FILTER`: the github repositories to include as a filter for PRs. It accepts comma-separated values.

## Examples

The command can be used in two ways:

- `gh pr` will retrieve the list of PRs you have been requested to do
- `gh pr <github_nickname>` will retrieve the list of PRs that have been requested to the given github account
