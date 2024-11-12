# EsepWebhook Lambda Function

This project contains a Lambda function that listens to GitHub webhook events and posts updates to a Slack channel whenever an issue is created.

## Files

- `Function.cs` - Main function handler.
- `aws-lambda-tools-defaults.json` - Configuration for Lambda deployment.
- `EsepWebhook.csproj` - Project file with dependencies.

## Setup

1. Deploy the Lambda function with `dotnet lambda deploy-function EsepWebhook`.
2. Configure GitHub and Slack integrations as described in the assignment.