

1. Support private S3 buckets
2. Support S3 encryption by default 
3. Support Proxy setup
4. Ensure tags in all the created resources
5. CIS benchmark 
   * AML bastion 
   * K8S
6. Simple upgrade -https://github.com/awslabs/amazon-eks-ami/issues/548

7. Simple integration to external modules ( Consul  , Promethuse etc) 
8.cloudwatch agent 
9. use export -import
Having a look at this quick start, the nested stacks are referenced from each other, with their templates all stored in S3. To break these stacks apart from each other, so they are separate stacks, would require considerable re-engineering of the templates to makes use of imports and exports rather than the outputs of each stack.
