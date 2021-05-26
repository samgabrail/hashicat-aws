# hashicat-aws
Hashicat: A terraform built application for use in Hashicorp workshops

Includes "Meow World" website.

[![CircleCI](https://circleci.com/gh/hashicorp/hashicat-aws.svg?style=svg)](https://circleci.com/gh/hashicorp/hashicat-aws)


## Doormat to push AWS creds to workspace
doormat --refresh
doormat aws --account se_demos_dev --tf-push --tf-workspace hashicat-aws --tf-organization HashiCorp-Sam