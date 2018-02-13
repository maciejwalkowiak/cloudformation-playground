- [cfn-flip](https://github.com/awslabs/aws-cfn-template-flip)
- [Practical VPC Design](https://medium.com/aws-activate-startup-blog/practical-vpc-design-8412e1a18dcc)
- https://www.youtube.com/watch?v=fpxDGU2KdkA

- **enable-termination-protection**

```
aws cloudformation create-stack --profile foo --stack-name mwa-test --template-body file://./vpc.json --enable-termination-protection
```

- to watch in 2018: drift detection

