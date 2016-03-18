Create AWS AMIs with packer
=============


##Goal
The goals of this project are to:
+ create ready-to-go AMI
+ deploy application very fast
+ speed up development workflow
+ easly and fast create and start new machines on test/production environment
+ not depends on vagrant boxes available publicly 


##Requirements
-----------
1. Packer v0.8.6:[download](http://www.packer.io/downloads.html) and follow installation guide http://www.packer.io/intro/getting-started/setup.html.
2. Virtualbox v5.0.14 [download](https://www.virtualbox.org/wiki/Downloads).
3. AWS CLI:
* Website: http://docs.aws.amazon.com/cli/latest/userguide/installing.html
VM import specification:
* Website http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/VMImportPrerequisites.html
Create a bucket in S3

aws ec2 describe-import-image-tasks --import-task-ids "import-ami-fh08peq4"

##Installation
-----------

Run script.sh to build the AMI and upload it to AWS:
```
$ ./script.sh varaibles.json
```
