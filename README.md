# Project Workflows

This folder contains GitHub workflows for the automatic management of the project.

## Setup

Before using these workflows, follow these setup instructions:

1. **Create a GitHub Token**: Generate a personal access token with appropriate permissions. This token will be used for authentication in the workflows.

2. **Save Token in Secrets**: Add the token to your repository secrets with the name `GH_TOKEN`.

3. **Update Project URL**: Modify the `PROJECT_URL` parameter in your secrets to match your project. The `PROJECT_URL` should be in the format `https://github.com/orgs|users/<ownerName>/projects/<projectNumber>`.

## Usage

After completing the setup, the workflows will automatically manage the project based on the defined configurations. Ensure that the workflows are properly configured and tailored to the specific requirements of your project.
