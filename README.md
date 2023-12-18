# Mass Emailing using AWS Lambda

**Table of Contents**
- [Project Overview](#overview)
- [Features](#features)
- [Setup](#setup-instructions)
  - [Prerequisites](#prerequisites)
  - [steps](#steps)


## Overview

This project is a solution for sending mass emails using AWS Lambda. AWS Lambda is a serverless computing service that allows you to run code without provisioning or managing servers.


## Features

- Integration with AWS SES: Seamless integration with Amazon Simple Email Service (SES).


## Setup Instructions

### Prerequisites

1. AWS Account: Ensure you have an AWS account set up with the necessary permissions to create and manage Lambda functions, IAM roles, and SES.

2. AWS CLI: Install the AWS Command Line Interface (CLI) for seamless interaction with AWS services from the command line.


### Steps

1. Fork the Repository:
   - After forking, clone your forked version of GitHub repository to your local development environment using the following command:
     ```bash
     git https://github.com/awsnigeriadevops/AWS_Lambda_Mass_Emailing.git
     ```

     *Please refer to [Contributing Guide](https://github.com/awsnigeriadevops/AWS_Lambda_Mass_Emailing/blob/main/CONTRIBUTING.md) to learn more*

2. Create an SES Configuration Set:
   - Log in to the AWS Management Console.
   - Navigate to SES and create a configuration set to track email sending events.

3. Set Up Lambda Function:
   - Reference the provided Lambda function code in your repo.
   - Create a new Lambda function in the AWS Management Console and upload the code.
   - Set up environment variables for SES credentials.

4. Configure IAM Role:
   - Create an IAM role with the necessary permissions for the Lambda function to send emails using SES.
   - Attach the IAM role to the Lambda function.

5. Set Up Trigger:
   - Use API Gateway endpoint to add a trigger for the Lambda function


6. Test and Monitor:
   - Test the Lambda function by triggering the configured event.
   - Monitor the SES console and CloudWatch logs for email sending status and errors.


