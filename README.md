# AWS Automation with Python and Lambda Functions

## Overview

This project automates various tasks on AWS using Python and AWS Lambda functions. It includes real-time file processing and organization within S3 buckets based on their creation date.

## Prerequisites

Before getting started, make sure you have the following resources set up:

- **IAM User with Programmatic Access**: Create an IAM user with programmatic access and necessary permissions to interact with AWS services.
- **Key Pairs**: Create SSH key pairs for secure access to AWS instances.
- **Public SSH Key on GitHub**: Add the public SSH key to your GitHub account for accessing repositories.
- **S3 Bucket**: Create an S3 bucket where files will be processed and organized.
- **Git Repository**: Create and clone a Git repository where your Python scripts will reside.

## Steps

Follow these steps to set up and deploy the automation:

1. **Write Python Script**: Develop a Python script to handle file processing and organization within the S3 bucket based on creation date.

2. **IAM Role for Lambda Function**: Create an IAM role for the Lambda function with permissions to access S3 and execute necessary actions.

3. **Lambda Function Creation**: Create a Lambda function in the AWS Management Console.

4. **S3 Trigger Configuration**: Add an S3 trigger to the Lambda function to execute it whenever a new file is uploaded to the specified bucket.

5. **Upload Python Code**: Upload your Python script to the Lambda function.

6. **Handler Settings and Test Event**: Update the handler settings in the Lambda function to point to your Python script. Create a test event to verify the function's behavior.

7. **Testing**: Test the Lambda function by uploading files to the S3 bucket and verifying that they are processed and organized correctly.

## Usage

Once the setup is complete, the automation will run seamlessly. Files uploaded to the specified S3 bucket will be automatically processed and organized based on their creation date.

## Notes

- Ensure that the IAM user has appropriate permissions to interact with AWS services.
- Keep your SSH keys secure and do not share them with unauthorized users.
- Regularly monitor the Lambda function's execution logs for any errors or unexpected behavior.

## Technologies Used
- Cloud Services: AWS (IAM, Lambda, S3)
- Programming Languages: Python
- Version Control: Git, GitHub
