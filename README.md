# AWS CDK Tutorial By Jonathan Moo
## Disclaimer
This is by no means the de facto way to do things. AWS CDK is relatively new, and there are too much information to digest. Hence, I'm writing on account of what I use in my daily work for knowledge sharing.

If you find anything useful or erratas, reach me and comment on my page at [https://gefyra.co/getting-started-with-aws-cdk/](https://gefyra.co/getting-started-with-aws-cdk/).

## How to use this Git repo?
This repo contains the code references in my website at:
[https://gefyra.co/category/tutorials/data-engineering/aws-cdk/](https://gefyra.co/category/tutorials/data-engineering/aws-cdk/)

Each tutorial will reference a git branch. For example, `Preparing Your AWS CDK Framework` will reference `CDK-T1`.

The master branch will contain the latest tutorial reference, but individual tutorials can be referenced by the branch name.

## Overview Of Tutorials
1. [Getting Started With AWS CDK](https://gefyra.co/getting-started-with-aws-cdk/) - No branch
2. [Preparing Your AWS CDK Framework](https://gefyra.co/preparing-your-aws-cdk-framework/) - [CDK-T1](https://github.com/jonathan-moo/gefyra-cdk-demo/tree/CDK-T1)
3. Creating An S3 Bucket With AWS CDK - [CDK-T2](https://github.com/jonathan-moo/gefyra-cdk-demo/tree/CDK-T2)
4. Creating A basic Lambda Function with AWS CDK - [CDK-T3](https://github.com/jonathan-moo/gefyra-cdk-demo/tree/CDK-T3)
5. Connecting S3 with Lambda on AWS CDK - [CDK-T4](https://github.com/jonathan-moo/gefyra-cdk-demo/tree/CDK-T4)

## How To Deploy
### Basic Lambda: [CDK-T3](https://github.com/jonathan-moo/gefyra-cdk-demo/tree/CDK-T3)
1. Run: `npm run build && cdk synth`
2. Run: `cdk deploy basicLambdaStack`
    * If you're running against with a customized profile, use: `cdk deploy <stack name> --profile <aws profile name>`# cdk-s3-lamda
# cdk-s3-lamda
# cdk-s3-lamda
