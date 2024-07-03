# Class6-assignment
## Steps to Create an Ubuntu Server on AWS:
## Sign in to AWS Console:

## Go to  AWS  Management Console and sign in with your credentials.

Navigate to EC2 Dashboard:

Click on "Services" at the top left, and under "Compute," select "EC2" to go to the EC2 Dashboard.

Launch Instance:

Click on "Instances" in the left sidebar and then click "Launch Instance" to start the instance creation process.

## Choose AMI (Amazon Machine Image):

Select "Ubuntu" as the operating system. Choose the Ubuntu version that suits your needs (e.g., Ubuntu Server 20.04 LTS).

Choose Instance Type:

Select an instance type based on your performance and resource requirements. For example, "t2.micro" is eligible for the AWS Free Tier.

## Configure Instance:

Configure instance details like the number of instances

Add Storage:

Specify the size and type of the root volume (EBS). The default settings are usually fine for most use cases.

## Add Tags (Optional):

Add tags to your instance for easier management and identification (e.g., Name: MyUbuntuInstance).

## Create Key Pair:

Select an existing key pair or create a new one. This key pair is used to securely connect to your instance via SSH.

## Launch Instance:

Click "Launch Instances" and AWS will start provisioning your Ubuntu server.

