# Amazon API Gateway REST API with HTTP integration in Terraform

This Terraform template deploys an Amazon API Gateway REST API endpoint with a simple public HTTP endpoint integration.

Learn more about this pattern at Serverless Land Patterns: [https://serverlessland.com/patterns/apigw-rest-api-http-integration-terraform](https://serverlessland.com/patterns/apigw-rest-api-http-integration-terraform)

Important: this application uses various AWS services and there are costs associated with these services after the Free Tier usage - please see the [AWS Pricing page](https://aws.amazon.com/pricing/) for details. You are responsible for any AWS costs incurred. No warranty is implied in this example.

## Requirements

* [Create an AWS account](https://portal.aws.amazon.com/gp/aws/developer/registration/index.html) if you do not already have one and log in. The IAM user that you use must have sufficient permissions to make necessary AWS service calls and manage AWS resources.
* [AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html) installed and configured
* [Git Installed](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
* [Terraform Installed](https://developer.hashicorp.com/terraform/downloads)

## Deployment Instructions

1. Create a new directory, navigate to that directory in a terminal and clone the GitHub repository:
    ``` 
    git clone https://github.com/aws-samples/serverless-patterns
    ```
2. Change directory to the pattern directory:
    ```
    cd apigw-rest-api-http-integration-terraform
    ```
3. From the command line, run:
    ```
    terraform init
    ```
4. From the command line, run:
    ```
    terraform plan
    ```
5. From the command line, run:
    ```
    terraform apply --auto-approve
    ```
## Testing

The stack will output the **api endpoint**. Visit that URL in your browser or make an HTTP request to the endpoint using *curl* to test the HTTP integration.
   
## Cleanup
 
1. To delete the stack, run:
    ```bash
    terraform destroy --auto-approve
    ```
----
Copyright 2023 Amazon.com, Inc. or its affiliates. All Rights Reserved.

SPDX-License-Identifier: MIT-0
