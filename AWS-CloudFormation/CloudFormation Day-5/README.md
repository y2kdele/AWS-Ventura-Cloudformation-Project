# AWS Ventura Cloudformation Project

## AWS Cloudformation CLI Command

- **AWS CLI Documentation:** https://docs.aws.amazon.com/cli/latest/reference/cloudformation/create-stack.html

- **Create  Stack Command:** 
aws cloudformation create-stack \
--stack-name Ventura-Prod-Env-Infra \
--template-body file://Ventura-Prod-Env-Infra.yaml \
--parameters file://Ventura-Prod-Env-Infra-parameters-file.Json 


