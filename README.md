# Localstack SNS Sample
LocalStack to create and test AWS SNS Topic on your local system using Terraform

# Terraform init 
terraform init

# Terraform Validate
terraform validate

# Terraform Apply
terraform apply

# Terraform Destroy
terraform destroy

# List SNS Subscription
aws --endpoint-url=http://localhost:4566 sns list-subscriptions

# Create New Message To Queue 
aws --endpoint-url=http://localhost:4566 sns publish  --topic-arn arn:aws:sns:us-east-1:000000000000:onexlab-sns-topic --message 'Welcome to Onexlab!'
