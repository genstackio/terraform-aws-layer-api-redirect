# AWS API Redirect Terraform module

Terraform module which creates a Lambda with a ready-to-use NodeJS source code to handle
redirect on AWS.

## Usage

```hcl
module "lambda-api-redirect" {
  source = "genstackio/layer-api-redirect/aws//modules/lambda"

  name   = "my-lambda-api-redirect"
}
```
