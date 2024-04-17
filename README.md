# Example of downloading and archiving a file from the internet in a repo

## Logic of the workflow
We use cron to schedule the workflow to run every 12 hours. The workflow downloads the file from the internet and archives it in the repo if it has changed.

Steps:
1. Clone the repo
2. Download the file
3. Use git commands to push to the repo if it has changed

## Why?
This is an example of how you can use GitHub Actions to automate tasks. You can use this as a template to automate tasks in your repo.

## Warning
This repo is only for educational purposes. Do not use it in production - the official list of IP addresses and hosts for GitHub is available at [GitHub's IP addresses](https://docs.github.com/en/enterprise-cloud@latest/authentication/keeping-your-account-and-data-secure/about-githubs-ip-addresses)

You can download the official [GitHub meta file](https://api.github.com/meta#) from the GitHub API.
