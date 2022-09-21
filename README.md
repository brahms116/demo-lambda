# Demo Lambda Function with API Gateway Proxy

This is a demo which builds an Api Gateway Proxy to a nodejs lambda function using AWS Code pipeline and AWS Code build. 

The code build instance was configured to use a custom image, using the SAM build image provided by AWS

[public.ecr.aws/sam/build-nodejs14](public.ecr.aws/sam/build-nodejs14)

### Todo

- [ ] refine code build role permissions.
