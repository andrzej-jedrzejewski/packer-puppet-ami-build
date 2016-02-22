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



Installation
-----------

Run Packer to build the AMI:
```
$ packer build quick-start.json
```