# AWS LocalStack

## Prerequirements
[Getting started - LocalStack](https://app.localstack.cloud/getting-started)
## Deploy stack
```bash
aws --endpoint-url=http://localhost:4566 cloudformation deploy --stack-name cfn-quickstart-stack --template-file "cfn-quickstart-stack.yaml"
```

## Delete stack
```bash
aws --endpoint-url=http://localhost:4566 cloudformation delete-stack --stack-name cfn-quickstart-stack
```