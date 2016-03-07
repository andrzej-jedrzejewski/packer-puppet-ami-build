Create AWS AMIs with packer
=============


Requirements
-----------
Packer v0.8.6:
* Website: http://www.packer.io
AWS CLI:
* Website: http://docs.aws.amazon.com/cli/latest/userguide/installing.html
VM import specification:
* Website http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/VMImportPrerequisites.html
Create a bucket in S3

aws ec2 describe-import-image-tasks --import-task-ids "import-ami-fh08peq4"

Installation
-----------

Run Packer to build the AMI:
```
$ packer build quick-start.json
```