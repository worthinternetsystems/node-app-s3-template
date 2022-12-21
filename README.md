# Node App S3 Template

## What is this for?
A simple way to deploy a free static site to an S3 bucket.

## How to use it?
- Use this template to create your own repository
- Set up an S3 bucket
- Set up a user with write access to the S3 bucket
- Add S3 bucket secrets to Github Settings > Security > Secrets > Actions
    - AWS_ACCESS_KEY_ID
    - AWS_PRODUCTION_BUCKET_NAME
    - AWS_REGION
    - AWS_SECRET_ACCESS_KEY