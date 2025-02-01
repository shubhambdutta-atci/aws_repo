create a nested CloudFormation stack to deploy a web application with multiple components.

Disclaimer :: Main stack is being operated with variablized form. not using any hardcoded format, using CloudFormation package template to create nested stack in CloudFormation.




IMPORTANT ::

Package Template creation command  (CLI)

<<  aws cloudformation package --template-file ./MyLambdaFunction.yml --s3-bucket my-bucket --s3-prefix cloudformation/packages --output-template-file ./MyLambdaFunction.packaged.yml  >>
