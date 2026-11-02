# Cloud-Storage-creation-S3-and-Launching-an-EC2-Instance-in-AWS
Ex.2 Cloud storage creation (S3) and launching an (Ec2) instance in AWS
Aim:
To create a Simple Storage Service (S3) in AWS and to launch an EC2 instance in AWS. 
Procedure
a)	Steps to Create a first S3 Bucket:
Step 1: Sign in to the AWS Management Console
Go to https://console.aws.amazon.com/s3.
Step 2: Open the S3 Service
In the console, type S3 in the search bar and select S3 to open the service dashboard.
Step 3: Create Bucket
Click the Create bucket button.
Step 4: Configure Bucket Settings
•	Bucket name: Choose a globally unique name.
•	AWS Region: Select the region where you want to store your data.
Step 5: Object Ownership
Choose between:
	ACLs disabled (recommended) – Bucket owner has full control.
	ACLs enabled – Control access via access control lists.
Step 6: Block Public Access Settings
By default, all public access is blocked. Leave it as-is unless you need public access.
Step 7: Bucket Versioning (optional)
Choose whether to enable versioning for objects in the bucket.
Step 8: Encryption (optional)
Select encryption options (SSE-S3, SSE-KMS, or none).
Step 9: Advanced Settings (optional)
Add tags, configure logging, etc.
Step 10: Create the Bucket
Click Create bucket at the bottom of the page.
b)	i. Steps to launch an EC2 Instance
1.	Go to the EC2 Dashboard in AWS Console.
2.	Click on “Launch Instance”.
3.	Choose an Amazon Machine Image (AMI) (e.g., Amazon Linux).
4.	Select an instance type (e.g., t2.micro for Free Tier).

5.	Create or choose a key pair for SSH access.
6.	Configure network settings (use default VPC/subnet).
7.	Configure storage (default root volume is fine).
8.	Review the settings and click “Launch Instance”.
9.	Wait for the instance to enter the running state.

c)	Step 3: Connect to Your Instance
•	Linux: Use SSH command with your .pem key.
•	Windows: Use RDP with decrypted admin password.

d)	Steps to Clean Up (Terminate the Instance)
1.	Go to EC2 Instances.
2.	Select your instance → Instance State → Terminate.


Snap Shots:
 

<img width="1920" height="1080" alt="Screenshot 2026-11-02 102859" src="https://github.com/user-attachments/assets/afbedaa0-9e2d-479e-a371-0bfd7d973ca4" />
<img width="1920" height="1080" alt="Screenshot 2026-11-02 102909" src="https://github.com/user-attachments/assets/4483bc81-661d-42ab-b3ee-954376a14c46" />
<img width="1920" height="1080" alt="Screenshot 2026-11-02 103256" src="https://github.com/user-attachments/assets/6af599e2-05b7-4445-a644-022d7bea4f28" />

<img width="1920" height="1080" alt="Screenshot 2026-11-02 104029" src="https://github.com/user-attachments/assets/9d913678-038b-414a-a634-ae9b943988b0" />
<img width="1920" height="1080" alt="Screenshot 2026-11-02 104205" src="https://github.com/user-attachments/assets/a1ab1379-0594-49ff-824f-71fcfb67abfa" />
<img width="1920" height="1080" alt="Screenshot 2026-11-02 104259" src="https://github.com/user-attachments/assets/d138a37f-d975-4053-bd94-e4ae6769626a" />

 <img width="1920" height="1080" alt="Screenshot 2026-11-02 104409" src="https://github.com/user-attachments/assets/b2d771bf-d288-41db-ac0c-036bd9b4eb21" />
<img width="1920" height="1080" alt="Screenshot 2026-11-02 104420" src="https://github.com/user-attachments/assets/db03dc32-0e77-4a7c-98a3-63d04792587e" />
<img width="1920" height="1080" alt="Screenshot 2026-11-02 104435" src="https://github.com/user-attachments/assets/bab361dd-aeeb-4966-8ee5-127f1222c2be" />


<img width="1920" height="1080" alt="Screenshot 2026-11-02 104857" src="https://github.com/user-attachments/assets/37219262-6e87-4a88-97da-46df1f48b520" />

<img width="1920" height="1080" alt="Screenshot 2026-11-02 104934" src="https://github.com/user-attachments/assets/9fd1d4eb-37c8-4847-89a0-62bd037fee9b" />

<img width="1920" height="1080" alt="Screenshot 2026-11-02 105442" src="https://github.com/user-attachments/assets/a00d5170-db5c-4e6c-8a31-031babf32454" />
 
Snapshot 5: Setting Internet gateway

<img width="1920" height="1080" alt="Screenshot 2026-11-02 110134" src="https://github.com/user-attachments/assets/87da970a-5fe3-488b-94a3-1189b70918dd" />


<img width="1920" height="1080" alt="Screenshot 2026-11-02 110335" src="https://github.com/user-attachments/assets/e2d74b5d-a291-43a5-a663-c01001095345" />
 
<img width="1920" height="1080" alt="Screenshot 2026-11-02 110419" src="https://github.com/user-attachments/assets/35b8ec3d-f54d-484d-8f29-385b64f17ae5" />

<img width="1920" height="1080" alt="Screenshot 2026-11-02 110450" src="https://github.com/user-attachments/assets/fe82e33a-03f8-410c-9e86-16386f261707" />

<img width="1920" height="1080" alt="Screenshot 2026-11-02 110508" src="https://github.com/user-attachments/assets/33c48401-c5ad-4832-a03a-1932b204c2b8" />

<img width="1920" height="1080" alt="Screenshot 2026-11-02 110930" src="https://github.com/user-attachments/assets/e64d8502-45ca-4fe9-843f-f3867210ea64" />
 
Snapshot 7: Creating route table

<img width="1920" height="1080" alt="Screenshot 2026-11-02 110939" src="https://github.com/user-attachments/assets/299cacae-ae92-4cce-84a7-770677ba0a10" />

<img width="1920" height="1080" alt="Screenshot 2026-11-02 103303" src="https://github.com/user-attachments/assets/2cf5ec29-b12c-404d-b2a4-e07f9f05020b" />

<img width="1920" height="1080" alt="Screenshot 2026-11-02 104029" src="https://github.com/user-attachments/assets/f026c4c9-845b-4aeb-96fa-7cb9f665b95a" />

<img width="1920" height="1080" alt="Screenshot 2026-11-02 104708" src="https://github.com/user-attachments/assets/43dd6c5f-9769-4bac-9fc9-14244cc72c74" />

<img width="1920" height="1080" alt="Screenshot 2026-11-02 104828" src="https://github.com/user-attachments/assets/6d839a91-f33d-46c2-990f-0955c7495732" />


<img width="1920" height="1080" alt="Screenshot 2026-11-02 105001" src="https://github.com/user-attachments/assets/91f225a4-67c7-4a5e-beb7-6760ad730adf" />

 
<img width="1920" height="1080" alt="Screenshot 2026-11-02 110147" src="https://github.com/user-attachments/assets/c74caac6-8722-4d61-bb45-95b7cd6dd91a" />


<img width="1920" height="1080" alt="Screenshot 2026-11-02 110253" src="https://github.com/user-attachments/assets/3edd82f6-bc50-4c49-857b-95b16722d703" />


<img width="1920" height="1080" alt="Screenshot 2026-11-02 110314" src="https://github.com/user-attachments/assets/24e97697-1d4e-4251-bbff-f1d63ea1fe59" />

<img width="1920" height="1080" alt="Screenshot 2026-11-02 110657" src="https://github.com/user-attachments/assets/8a71f868-0576-47a4-98b3-8d98f58e7693" />

<img width="1920" height="1080" alt="Screenshot 2026-11-02 110723" src="https://github.com/user-attachments/assets/f8f5807c-2296-4f63-8d92-df1a36cb163d" />

<img width="1920" height="1080" alt="Screenshot 2026-11-02 110733" src="https://github.com/user-attachments/assets/b04dffa7-19a6-4a9e-a37a-0934e2e37b88" />



























Result:
Thus, a Simple Storage Service (S3) and EC2 (Elastic Compute Cloud) - instance has been successfully created and launched in AWS
 
