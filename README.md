# Cloudformation Template

## Workflow diagram

![alt](https://github.com/mountain-chan/cloudformation-template/blob/main/workflow_diagram.png)

## Validate template
```
sam validate --template-file template.yaml 
```
## Deploy template
```
sam deploy --template-file template.yaml --stack-name CHAN-Demo-ECS --s3-bucket chan-demo-ap-southeast-1 --capabilities CAPABILITY_IAM CAPABILITY_NAMED_IAM --region ap-southeast-1
```