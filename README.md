# ansible_aws_assignment
This is a sample playbook for:
1. Creating 2 ec2 instances and an ELB in AWS.
2. Installing nginx on the instances and printing their public ip's.
3. Adding both the instances in the ELB.

AWS Access Key and Secret Access Key has been passed as a global variable.
The file pass.yml is been used for storing AWS credentials and has been encrypted using ansibale-vault.
