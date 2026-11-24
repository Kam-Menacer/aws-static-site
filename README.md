# AWS Static Site

A static website hosted on Amazon S3 and served globally through CloudFront.

## Architecture
- S3 bucket (private) stores index.html
- CloudFront distribution serves the site over HTTPS
- Origin access control: only CloudFront can read the bucket

## What I learned
- How S3 and CloudFront work together
- Keeping a bucket private and serving content securely
- Default root object and cache behaviour

Live site: https://difzpthtumnoc.cloudfront.net
