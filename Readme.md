Aws Script for AWS Management
This python script can be used to manage a AWS endorsement.

This provides features like :

EC2 :
Create your own Key based SnapShots
Delete SnapShots
Delete/ Terminate any EC2 instance which does not have a user/ any specific tag
stop any useless Running Ec2 instance
RDS :
delete RDS Instance
Delete RDS Cluster
Stop any useless Running RDS Cluster/Instance
Delete useless Snapshots
Delete any RDS Instance or Cluster which does not have a specific tag with it
Delete any RDS Snapshot that is older then 2 days
these Scripts can directly be used with AWS lambda function for Automation purposes as well

Installation
First of all install python on your system.

pip install boto3