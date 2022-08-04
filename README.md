## Transit gateway with shared VPC in single account quickstart solution for AWS China region

## Networking architecture diagram

This CloudFormation template will create networking layout as below diagram (only included AWS Cloud part).

![](https://d51vuyprlknbq.cloudfront.net/TGW-SharedVPC/Architecture.png)

## How to deploy

* Clone this repository to get all cloudformation in a S3 bucket in your AWS account
* Make main template to public on S3, and get public access URL
* Use this URL in CloudFormation, choose your EC2 Key file, and create stack
* Check CloudFormation output to get login information

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

