# set env vars for gitlab terraform state access

script to set environment variables for accessing GitLab Terraform state

usage: `source set_env_vars_for_gitlab_terraform_state_access`

The following environment variables have to be set before calling the script

- `GITLAB_URL`

   the url of the GitLab instance

- `GITLAB_PROJECT_ID`

   the project id of the GitLab project

- `TF_USERNAME`

   the username to authenticate access to the terraform state

- `TF_PASSWORD`

   the password (or token) to authenticate access to the terraform state

- `TF_STATE_NAME`

   the name of the terraform state

These variables can be set by the script set_env