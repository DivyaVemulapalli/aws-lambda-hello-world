# AWS Lambda Hello World Project

##  Project Overview

Created and deployed a serverless AWS Lambda function using Python. The function was tested using AWS Lambda test events and successfully returned a response without requiring any server infrastructure.

##  AWS Services Used

- AWS Lambda
- AWS IAM (Execution Role)
- CloudWatch Logs
  
##  Steps Followed

1. Opened AWS Lambda Console
2. Created a new Lambda function
3. Selected Python runtime
4. Added Python code
5. Deployed the function
6. Created a test event
7. Executed the function
8. Verified successful response

##  Lambda Code

```python
def lambda_handler(event, context):
    return {
        'statusCode': 200,
        'body': 'Hello from AWS Lambda!'
    }
```

##  Test Result

```json
{
  "statusCode": 200,
  "body": "Hello from AWS Lambda!"
}
```

##  Outcome

Successfully created and tested a serverless AWS Lambda function using Python and gained hands-on experience with AWS Lambda deployment and execution.

##  Key Learnings

- Introduction to Serverless Computing
- AWS Lambda Function Creation
- Lambda Deployment Process
- Test Events
- Function Execution
- CloudWatch Integration
