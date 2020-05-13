## Backend

This script is pre-configured to use the Terraform Cloud backend.

1. Edit the backend settings in `backend.tf`

2. Add a [GitHub secret](https://help.github.com/en/actions/configuring-and-managing-workflows/creating-and-storing-encrypted-secrets) called `TF_API_TOKEN` with a [Terraform Cloud team token](https://www.terraform.io/docs/cloud/users-teams-organizations/api-tokens.html#team-api-tokens) as its value

> Don't forget to set the environment variables or any other variable in your Terraform Cloud workspace
