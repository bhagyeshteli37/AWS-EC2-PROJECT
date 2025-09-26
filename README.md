# AWS-EC2-PROJECT
EC2 Instance creation step by step guide with RedHat AMI

step1: EC2 Dashboard
AWS Console → EC2 → Instances → Launch Instance

Step 2: Name and Tags`
Name: My-RedHat-Server
(Optional) Tags (ex: Project=AWS, Env=Dev)

step3: Application and OS Images (AMI)
Amazon Machine Image (AMI)
Example: Red Hat Enterprise Linux 9 (HVM), SSD Volume Type – Free tier eligible

Step4: Instance Type
Hardware configuration 
Example: t2.micro (Free Tier Eligible)

Step 5: Key Pair (SSH Access)
Agar Key Pair select
Agar → Create new key pair → Download .pem file → secure
key SSH login

Step 6: Network Settings
VPC + Subnet choose(default VPC use )
Security Group:
Existing Security Group select 
Example: Allow SSH (22) from My IP + Allow HTTP (80) + Allow HTTPS (443

Step 7: Storage (Default Settings)
8GB General Purpose SSD (gp3/gp2) default 
increase 

Step 8: Launch Instance
settings check → Launch Instance
EC2 server 
