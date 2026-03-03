# aws-cheatsheet

## Test with a simple API call

  aws s3 ls --profile YOUR_PROFILE_NAME

## Use the default profile

  aws sts get-caller-identity

## List configured profiles

  aws configure list-profiles

## Inspect a profile’s config
  
  aws configure list --profile YOUR_PROFILE_NAME

# get cloudformation RDS endpoint

  aws cloudformation describe-stacks   --stack-name wordpress-rds   --query "Stacks[0].Outputs[?OutputKey=='RDSEndpoint'].OutputValue"   --output text
