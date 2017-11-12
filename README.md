# fork-auto-sync-demo
This repo demos any push to the upstream will get automatically synced with specified downstream by publishing the Github events to an AWS SNS topic, the SNS will then invoke an AWS Lambda function to perform a pull on the downstream using Github APIs.

test-21
