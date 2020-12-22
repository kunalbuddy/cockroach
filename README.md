# labs-cockroach

## setup
* `export AWS_PROFILE=xxxxxxxx`
* `terraform plan -var-file=cockroach.tfvars -state=cockroach.tfstate cockroach`
* `terraform apply -var-file=cockroach.tfvars -state=cockroach.tfstate cockroach`
* `cockroach init --certs-dir=certs --host=<@ip of one host>`


## AWS Regions (examples)
- "us-west-1"
- "eu-west-1"
- "cn-northwest-1"
- "ap-southeast-1"