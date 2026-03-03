# aws-cheatsheet

## Test with a simple API call

  aws s3 ls --profile YOUR_PROFILE_NAME

## Use the default profile

  aws sts get-caller-identity

## List configured profiles

  aws configure list-profiles

## Inspect a profile’s config
  
  aws configure list --profile YOUR_PROFILE_NAME
