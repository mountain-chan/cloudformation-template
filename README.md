# AWS Cloudformation Template Example

### This template will automatically build everything in the diagram below

![alt](https://github.com/mountain-chan/cloudformation-template/blob/main/workflow_diagram.png)

## Validate template
```
sam validate --template-file template.yaml 
```
## Deploy template
```
sam deploy --template-file template.yaml --stack-name <Stack-Name> --s3-bucket <Bucket-Name> --capabilities CAPABILITY_IAM CAPABILITY_NAMED_IAM --region <Region-Id>
```

**AWS CloudFormation Documentation**: https://github.com/awsdocs/aws-cloudformation-user-guide/tree/main/doc_source
