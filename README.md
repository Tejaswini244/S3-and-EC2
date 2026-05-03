
# EX NO: 2 CLOUD-STORAGE-CREATION-S3-AND-LAUNCHING-AN-EC2-INSTANCE-IN-AWS-

NAME: R. TEJASWINI

REGISTER NUMBER: 212224230218
# AIM :
To create an AWS account, set up a root user, and create an IAM user with specified permissions.

# PROBLEM STATEMENT :
This experiment involves creating an AWS account, configuring security settings for the root user, and setting up an IAM user. IAM users allow for secure, managed access to AWS resources without exposing the main account's root credentials.

## Procedure:
# Sign in to the AWS Management Console:
• Go to the AWS Management Console and log in with your AWS credentials.
# Navigate to the EC2 Dashboard:
• Once logged in, locate and click on the "EC2" service in the AWS Management Console.
# Launch an Instance:
• On the EC2 dashboard, click the "Launch Instance" button.
# Choose an AMI (Amazon Machine Image):
• Select the operating system and software you want to use for your instance (e.g., Amazon Linux, Ubuntu, Windows).
• Click "Select" to choose the AMI.
# Choose an Instance Type:
• Select the type of instance you need (e.g., t2.micro, m5.large) based on your workload requirements.
• Click "Next: Configure Instance Details".
# Configure Instance Details:
• Set the number of instances to launch, the availability zone, and other optional settings like networking and security.
• Click "Next: Add Storage".
# Configure Storage:
• Specify the size and type of storage for your instance.
• Click "Next: Add Tags".
# Add Tags (Optional):
• Add tags to your instance for easier identification and management.
• Click "Next: Configure Security Group".
# Configure Security Group:
• Choose or create a security group to control inbound and outbound traffic to your instance.
• Click "Review and Launch".
# Review and Launch:
• Review all the configurations and click "Launch".
Create a Key Pair (if you haven't already):
• You'll be prompted to create a new key pair or choose an existing one.
• Download the key pair (.pem file) and store it securely.
# Launch the Instance:
• Click "Launch Instance" to start the instance creation process.
# Connect to your Instance:
• Once the instance is running, you can connect to it using SSH (for Linux) or RDP (for Windows).
• Use the key pair you downloaded earlier to connect.

# output
<img width="1142" height="604" alt="image" src="https://github.com/user-attachments/assets/4e23f48c-a9bd-4101-805c-6f7fde739a86" />

<img width="1151" height="633" alt="488135555-648cccd7-e6c6-4fa8-a8ca-a52d1e4c5186" src="https://github.com/user-attachments/assets/77bc8668-13b1-495d-ab46-87059d436618" />

<img width="1152" height="593" alt="488135613-efa940ab-f5f9-421b-be5e-ccac608865e0" src="https://github.com/user-attachments/assets/253a9ccb-9c89-4389-b6b6-31ac62411635" />

<img width="1152" height="635" alt="488135674-932bd786-df15-4c2d-9bf9-a9d14229c21d" src="https://github.com/user-attachments/assets/71fe69cd-1b10-4134-919b-2c7268e59156" />

# RESULT
The AWS account was successfully created, with set up for the root user . Additionally, an IAM user was created with specified permissions, allowing for secure, controlled access to AWS resources without the use of the root account.
