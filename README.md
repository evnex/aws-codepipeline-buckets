# aws-codepipeline-buckets
Consolidated bucket per region for CodePipeline use

## Usage
Deploy `bucket.yml` via Cloudformation or Cloudformation StackSets (for multi-region deployments). There are Parameters to define access to an Organization or a list of IAM Principals, allowing cross-account use of CodePipeline actions to those accounts.

If you do not specify settings for Organization or Cross-Account access, the Bucket will be usable only in the Account where the Bucket is deployed.