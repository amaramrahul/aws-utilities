# aws-utilities

Wrapper convenience scripts for ec2 commands. For ex:

$ ec2-ssh-instance webserver*

will try to find the EC2 instance whose name begins with webserver and logs into it. If there are multiple instances matching the Name pattern, they are displayed. You can choose one of them randomly by passing "--random" option.
