

Inorder to deploy the s3 bucket and upload your code into it:
Use aws cloudformation create-stack --stack-name s3Stack --template-body file://S3_Stack.yml 

To deploy the stack :
aws cloudformation create-stack --stack-name LambdaFunction --template-body file://LambdaStack.yml --capabilities "CAPABILITY_NAMED_IAM" to deploy the stack.

And we can delete the stack using aws cloudformation delete-stack --stack-name LambdaFunction
