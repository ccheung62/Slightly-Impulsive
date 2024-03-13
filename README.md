# Slightly Impulsive
A serverless website that personalizes online shopping by adding AI-generated product suggestions based on user's request. This website aims to make the online shopping experience more recommendation-based rather than a treasure hunt. User queries would be used to invoke an AWS Lambda function through a custom API endpoint created in Amazon API Gateway to fetch a product suggestion from OpenAI API. Each product suggestion is stored using DynamoDB and displayed on the Global History page. The website is deployed using AWS Amplify. 

![](/images/website.png)

## Technical Architecture Diagram 
![](/images/diagram.png)

## Technical Stack 
### React
React is used to create the frontend of the website and showcase the AI-generated product suggestions

### AWS Lambda
Lambda is used to fetch results from OpenAI API and read/write to DynamoDB. 

### Amazon API Gateway
Amazon API Gateway is used to connect the Lambda functions to the frontend. 

### DynamoDB
DynamoDB is a NoSQL database used to store generated product suggestions. The data is stored in a DynamoDB table.

### AWS Amplify
AWS Amplify is used to deploy and host the website

## Website Link
The website is deployed [here](https://main.d2a8r41qu5eshh.amplifyapp.com/)





