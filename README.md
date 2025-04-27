Iniate terraform with 

terraform init

Download the AWS cli from:

https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html

Once installed configure aws for sso login:

aws configure sso --profile terraform

Once configured you can login with

aws sso login --profile terraform