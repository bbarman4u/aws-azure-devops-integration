# Welcome to your CDK TypeScript project!

You should explore the contents of this project. It demonstrates an AWS CDK app with an instance of a stack (`FirstCdkProjectStack`)
which contains an Amazon SQS queue that is subscribed to an Amazon SNS topic.

The `cdk.json` file tells the CDK Toolkit how to execute your app.

## Useful commands

 * `npm run build`   compile typescript to js
 * `npm run watch`   watch for changes and compile
 * `npm run test`    perform the jest unit tests
 * `cdk deploy`      deploy this stack to your default AWS account/region
 * `cdk diff`        compare deployed stack with current state
 * `cdk synth`       emits the synthesized CloudFormation template

## Building and Deploying as Part of a Pipeline
The accompanying Azure DevOps Pipeline YAML file can be used to run the build and deploy the cloud formation stacks to AWS.
