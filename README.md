# Get GitHub Stargazers

This is the repository for collecting the GitHub Stargazers for a specific repository. In this case we will be using it to collect the Stargazers for the direktiv/direktiv repository.

## Workflow overview

The workflow is an example of how to query the GitHub API for the following information:
 - Amount of stars for a specific repo (in this case `direktiv`)
 - Iterate over the amount of return values (following `links` or count of `pages` returned in the API call)
 - For each Stargazer, try and get their email address from GitHub if configured
 - Compile this in a CSV file

## Variables

 - None

## Secrets

 - GITHUB_TOKEN: GitHub PAT token access for the repository (if not public)

## Namespace Services

 - None

## Input examples

- None
