# S3-Lambda-and-DynamoDB-Event-driven-architecture
### This project will use the cloud formation template to create an S3 bucket, a lambda function, a Dynamo DB table, and an IAM role. 


![dynamodb_pattern1](https://github.com/user-attachments/assets/731fe041-462d-403d-9254-18038bd07832)

### The project aims to capture and save the metadata of any object uploaded or deleted from a specific S3 bucket. We create an S3 notification that triggers the lambda function, which saves the object metadata into a Dynamo DB table.
