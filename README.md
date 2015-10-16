# aws-utilities

Wrapper convenience scripts for ec2 commands. For ex:

$ ec2-ssh-instance webserver\*

will try to find the EC2 instance whose name begins with webserver and logs into it. If there are multiple instances matching the Name pattern, they are displayed. You can choose one of them randomly by passing "--random" option.

This has been tested with the following ubuntu packages:

ec2-api-tools_1.6.12.0-0ubuntu1_all.deb
ascli_1.0.61.0-1_all.deb
elbcli_1.0.17.0-0ubuntu1_all.deb
moncli_1.0.12.1-1_all.deb

TODO
----

Need to migrate the scripts to use awscli
