# fork-auto-sync-demo
This repo functions as the upstream and publishes Github events to an AWS SNS topic, the SNS will then invoke an AWS Lambda function to sync the downstream fork using Github APIs.
