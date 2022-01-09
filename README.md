# Bankuish Challenge

## Reason for the solution
 A serverless solution saves the dev team to worry about scalability and the company can save money since we just going to pay for what we use. I chose AWS as a provider but this solution can be replicated in several providers

## Technical explanation

In that solution all communication will be through the API Gateway to assure the safety of the APIs and control the logs and routes, the Rest API’s will be made using lambda and the CVS integration I’ll use SQS, the consumer will read from this queue and will save the files in the S3 service and the handled info in the DocumentDB, to finalize the database used by the Rest APIs will be an RDS but can be other databases depending on the requirement.

![alt text](https://github.com/gigandre/bankuish/blob/master/Bankuish.png?raw=true)
