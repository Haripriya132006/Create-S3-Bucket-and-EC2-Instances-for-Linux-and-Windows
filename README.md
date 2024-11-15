 # CREATE S3 BUCKET AND EC2 INSTANCES FOR LINUX AND WINDOWS
  ## AIM
       To Create S3 bucket and EC2 Instances for Linux and Windows.
## PROBLEM STATEMENT
    Explain about the Experiment.

## ALGORITHM
 ### Steps 1:
 **Login to AWS Management Console:**
1. Open the AWS Management Console.
2. Navigate to the **S3** service for bucket creation and **EC2** for instance setup.

 ### Steps 2:
**Create an S3 Bucket:**
1. Go to the S3 service.
2. Click on **Create bucket**.
3. Provide a unique **Bucket Name** and select the **Region**.
4. Configure additional settings as per requirements and click **Create bucket**.
 
 ### Steps 3:
 **Launch EC2 Instance (Linux):**
1. Go to the EC2 service.
2. Click **Launch Instance**.
3. Select an **Amazon Machine Image (AMI)**, such as Amazon Linux 2.
4. Choose an **Instance Type** (e.g., t2.micro).
5. Configure instance settings, key pair, and security groups, then **Launch** the instance.

 ### Steps 4:
 **Launch EC2 Instance (Windows):**
1. Repeat the EC2 launch steps but select a **Windows Server AMI**.
2. Complete instance configuration and **Launch**.
 
 ### Steps 5:
 **Connect to Instances:**
1. **Linux Instance**: Use SSH to connect.
   ```bash
   ssh -i "key_pair.pem" ec2-user@<linux_public_dns>

## COMMANDS

### S3 Bucket Creation
#### 1.AWS CLI Command:
aws s3 mb s3://<your-bucket-name> --region <your-region>
## EC2 Instance (Linux) Commands
Launch Linux EC2 instance and set up SSH access.
## EC2 Instance (Windows) Commands
Launch Windows EC2 instance and connect using RDP.

## OUTPUT
### S3 bucket
![Screenshot 2024-11-15 163704](https://github.com/user-attachments/assets/f399e94d-68bd-4fbb-8cf5-715c91f6c483)
![Screenshot 2024-11-15 163724](https://github.com/user-attachments/assets/86f40ea1-aeaa-4844-88fd-e32122244636)
![Screenshot 2024-11-15 163741](https://github.com/user-attachments/assets/f49ab5be-fd0f-4298-8490-9c6939925e26)


### linux instance
![Screenshot 2024-11-15 164111](https://github.com/user-attachments/assets/4f9695c0-2224-40f0-bf0f-c2bff8e00243)
![Screenshot 2024-11-15 164129](https://github.com/user-attachments/assets/a132daea-51bd-459f-8d43-6e04398098a8)


### windows instance
![Screenshot 2024-11-15 164146](https://github.com/user-attachments/assets/7e4d3452-8553-4314-a2a1-567070997f74)

### REG NUMBER: 212223220030
### NAME: HARIPRIYA K
 
 ## RESULT
 The experiment to create an S3 bucket and launch EC2 instances for Linux and Windows is successfully completed.

  


