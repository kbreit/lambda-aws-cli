# lambda-aws-cli

This repository provides the `aws` command for AWS Lambda layers. AWS only provides boto3 access which sometimes isn't as convenient as using the `aws` commands. There are two ways to use this layer.

The first, and probably easiest, is to import it into your function using this arn:

```arn:aws:lambda:us-east-2:804798220069:layer:awsCLILayer:6```

Alternatively you can:

1. Clone the repository
2. Zip everything, excluding this README file
3. Create a new layer from the main AWS Lambda page
4. Upload zip file


| aws-cli version |  ARN |
| --- | --- |
| 0 |  `arn:aws:lambda:us-east-2:804798220069:layer:awsCLILayer:6` |
