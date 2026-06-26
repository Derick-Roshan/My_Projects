# Roshan R - Project Portfolio

This repository contains my academic and personal projects related to AWS Cloud, DevOps, Linux, Machine Learning, and Web Development.

## Skills Demonstrated

- AWS EC2
- Linux Administration
- Terraform
- Git & GitHub
- Terraform
- Jenkins
- Machine Learning
- HTML & CSS

## Projects

### Project 1: Motor Predictive Maintenance

- Developed a Machine Learning application to predict motor failures using sensor data.
- Deployed and hosted the Streamlit application on an AWS EC2 instance running Amazon Linux.
- Configured the server and accessed the application through the EC2 public IP.
- Technologies: Python, Streamlit, Scikit-Learn, AWS EC2, Amazon Linux, Git
- Repository: https://github.com/Derick-Roshan/Predictive_maintanance
- Screenshots:

  
  Step 1: Launching an Amazon Linux EC2 instance.
  <img width="314" height="206" alt="image" src="https://github.com/user-attachments/assets/9e8dd321-e618-4f23-acaf-f7f401c50938" />

  Step 2: Selecting the Amazon Linux AMI (64-bit).
  <img width="374" height="150" alt="image" src="https://github.com/user-attachments/assets/a576bd7e-1d25-4771-9607-cd6d1bf0353b" />

  Step 3: Choose an EC2 instance type (t2.medium for this deployment). Becouse the particuler Application need huge performance.
  <img width="820" height="338" alt="image" src="https://github.com/user-attachments/assets/8cbdf5cb-9168-4c2d-9135-57313299361f" />

  Step 4: Creating a key pair for secure SSH access to the EC2 instance. 
  <img width="578" height="402" alt="image" src="https://github.com/user-attachments/assets/7c707943-d37c-49b9-9d8d-ae30a17773aa" />

  Step 5: Configure the security group to allow HTTP (port 80) and the application port (e.g. 8502) so the application is accessible from a browser.
  <img width="372" height="177" alt="image" src="https://github.com/user-attachments/assets/7c0e6f62-af49-4a40-8511-43a32086ee0f" />

  Configured the Storage as 30GB.
  <img width="830" height="324" alt="image" src="https://github.com/user-attachments/assets/f24616d5-c9ef-4108-96da-2540a0fb2231" />

  Number of instance is 1. and clicked on Launch instance.
  <img width="340" height="474" alt="image" src="https://github.com/user-attachments/assets/59d576da-7d93-4b03-aec8-2a936a0f6fa5" />

  You can see that Instance is running.
  <img width="832" height="256" alt="image" src="https://github.com/user-attachments/assets/85d27b3e-f11b-4e5b-969d-38669c5ccb87" />

  I copied a IP address for connecting the Linux server.
  <img width="830" height="190" alt="image" src="https://github.com/user-attachments/assets/4be27530-b703-4e41-ba06-853a1608151d" />

  This is how I connect the Linux server.
  <img width="830" height="388" alt="image" src="https://github.com/user-attachments/assets/7ef08771-8959-41b5-80eb-1caf420da8db" />

  We need to install HTTPD, python3, git, pip3.

  We need to clone the project from the github repo.
  <img width="830" height="398" alt="image" src="https://github.com/user-attachments/assets/42eda8dc-6b9b-4b6c-8bed-b7e8f765c63a" />
  <img width="830" height="228" alt="image" src="https://github.com/user-attachments/assets/1f69d0d6-ed3d-47ae-945a-5fd4b1f3cec9" />

  Then we need to download the packages and libraries which we used in the python.
  <img width="832" height="104" alt="image" src="https://github.com/user-attachments/assets/0d13b82a-6c24-4067-bddd-ddca70bdaa4d" />
  <img width="830" height="296" alt="image" src="https://github.com/user-attachments/assets/8daa726b-0d55-4b83-ad29-73e5beb91226" />
  <img width="415" height="180" alt="image" src="https://github.com/user-attachments/assets/e89f3ea0-6eeb-4ce9-99ec-43bfee14d9c6" />
  <img width="830" height="400" alt="image" src="https://github.com/user-attachments/assets/dca79aec-f952-45a7-be8a-c954ef8c722b" />
  <img width="830" height="360" alt="image" src="https://github.com/user-attachments/assets/962c057b-1be6-42d5-b695-0ad9a671a560" />
  <img width="830" height="84" alt="image" src="https://github.com/user-attachments/assets/b14c60ae-3ee1-4b45-98e1-82f969db3afa" />

  After installing the python packages and if we need to run the project you can see that is running in the bare mode.
  <img width="832" height="358" alt="image" src="https://github.com/user-attachments/assets/5138e983-d84a-409b-b628-60501f78e19b" />

  To sort it out:
  Now you see that the after using nohup command the prject is running in the background.
  <img width="830" height="292" alt="image" src="https://github.com/user-attachments/assets/e1f5492f-2499-4518-8966-68e497d4b4c6" />

  To view the project Iam using the chrom browser. (On incognito tab - Becouse it wont store history or cookies)

  http://IP address: 8502

  Before that we need to check wheather inbound rules on Security groups has been added - TCP, Port & Source.
  <img width="828" height="266" alt="image" src="https://github.com/user-attachments/assets/e24d914b-e7f4-479d-8b2a-197f8f918823" />

  After saving - I entered a IP address and Port number to view the project.
  <img width="830" height="278" alt="image" src="https://github.com/user-attachments/assets/55e12e7c-b7e4-4a97-bafa-a512f76cdd5c" />

  You can see that the project has been deployed Successfully.
  <img width="830" height="460" alt="image" src="https://github.com/user-attachments/assets/f3a72868-95c3-4856-ae55-96c960f2ad11" />

-------------------------------------------------------------------------------------------------------------------------------------------------------


### Project 2: Portfolio Website Hosting on AWS EC2
- Static website deployed on AWS EC2.
- Technologies: HTML, CSS, AWS EC2, Linux
- Repository: https://github.com/Derick-Roshan/Portfolio-website
- Screenshots:

This is Portfolio website created with HTML & CSS, uploaded on github.
<img width="364" height="192" alt="image" src="https://github.com/user-attachments/assets/1ce936ed-034c-426e-85c3-2c5f318f63ab" />

Creation of instance on aws.
<img width="380" height="168" alt="image" src="https://github.com/user-attachments/assets/ce002e77-c8a8-4461-b48d-a6f68517477d" />
<img width="379" height="164" alt="image" src="https://github.com/user-attachments/assets/2a0712ba-66c2-4cb5-931c-3976a2ec4caf" />

Connecting the Amazon-linux server.
<img width="297" height="147" alt="image" src="https://github.com/user-attachments/assets/ccd70ae5-e8bf-403a-8646-9ed370504d63" />

We need to install HTTPD and GIT before cloning the website project from github.
<img width="307" height="124" alt="image" src="https://github.com/user-attachments/assets/0e31ef15-4f0c-412a-afbb-d1da422eb23c" />

We have to keep the particular project in the var/www/html path.
<img width="416" height="106" alt="image" src="https://github.com/user-attachments/assets/91b907d5-4e80-4e08-b863-e01c7cc2df0b" />

Copy past the ip address to see the Output.
<img width="416" height="152" alt="image" src="https://github.com/user-attachments/assets/de5ce918-07f8-4450-87fc-352a386939d8" />

Here you go!
<img width="415" height="219" alt="image" src="https://github.com/user-attachments/assets/ba1a1b22-2078-49b0-9a67-e65f42010e76" />

-------------------------------------------------------------------------------------------------------------------------------------------------------
### Project 3: Terraform Web Server Automation
- Automated EC2 provisioning using Terraform.
- Technologies: Terraform, AWS, Git
- Repository: https://github.com/Derick-Roshan/web-server-terraform
- Screenshots: Coming Soon

### Project 4: Static Website Hosting on Amazon S3

- Hosted a static portfolio website using Amazon S3 Static Website Hosting.
- Configured bucket permissions and enabled public access for website hosting.
- Uploaded HTML, CSS, and image assets to the S3 bucket.
- Accessed the website using the S3 static website endpoint.
- Technologies: HTML, CSS, Amazon S3, AWS
- Repository: https://github.com/Derick-Roshan/Portfolio-website
