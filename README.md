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

---------------------------------------------------------------------------------------------------------------------------------------------------------


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

---------------------------------------------------------------------------------------------------------------------------------------------------------
### Project 3: Terraform Web Server Automation
- Automated EC2 provisioning using Terraform.
- Technologies: Terraform, AWS, Git
- Repository: https://github.com/Derick-Roshan/web-server-terraform
- Screenshots:

This is my terraform files stored in Github repo.
<img width="415" height="168" alt="image" src="https://github.com/user-attachments/assets/12de0576-71e4-4a23-bb86-fa66305c2fa4" />

Main.tf
<img width="402" height="284" alt="image" src="https://github.com/user-attachments/assets/3f1b9c8e-c757-4548-b78e-6001d1043fa8" />
<img width="322" height="285" alt="image" src="https://github.com/user-attachments/assets/14ae1bce-6df0-4fbd-a2cf-62d19d7873ef" />
<img width="328" height="327" alt="image" src="https://github.com/user-attachments/assets/887b65cd-7a2c-487b-b076-b0d7bfa6f1fd" />
<img width="365" height="264" alt="image" src="https://github.com/user-attachments/assets/2317f3f3-8f86-48ac-bf8c-6eec1bdaaa0c" />

Provider.tf
<img width="296" height="147" alt="image" src="https://github.com/user-attachments/assets/d08f1ce9-60ce-4775-8811-4ce3c3f31ee5" />

Output.tf
<img width="302" height="150" alt="image" src="https://github.com/user-attachments/assets/4ddc1a9d-a0dc-4516-afb3-8a8bfda7d72e" />

Now I am opening the terminal and cloning the project to my local.
<img width="352" height="189" alt="image" src="https://github.com/user-attachments/assets/93270027-9d70-4922-86c6-a59aafbd1b29" />

Now initiating the terraform. (terraform init)
<img width="361" height="180" alt="image" src="https://github.com/user-attachments/assets/669c9c01-647b-4d5f-97ed-10ce9f652c1b" />

Now going to AWS to create the “access key” on “Security credentials”
<img width="476" height="150" alt="image" src="https://github.com/user-attachments/assets/0e8151f4-3d36-4ea6-9387-ded6dec96a7c" />
<img width="415" height="138" alt="image" src="https://github.com/user-attachments/assets/6c6709c9-d3d7-42ad-aa37-2d506bbcec3b" />
<img width="416" height="193" alt="image" src="https://github.com/user-attachments/assets/56f42118-6ae9-4156-95cb-3505a8534146" />

Copy and paste the credentials into the terminal to configure the AWS CLI.
<img width="415" height="78" alt="image" src="https://github.com/user-attachments/assets/11baf560-7a7e-43ad-abc1-b0291be92ed8" />

Terraforom plan
<img width="383" height="205" alt="image" src="https://github.com/user-attachments/assets/a11fd19b-82b4-47b8-ae92-b59b44df03ee" />

This is because I didn’t give the permission for key-pair.
<img width="416" height="221" alt="image" src="https://github.com/user-attachments/assets/180d1bc0-18b4-47aa-b66d-067b7be568a2" />

Terraform apply:
<img width="415" height="149" alt="image" src="https://github.com/user-attachments/assets/33427df9-8d10-4d6d-9233-fdaeb41529ea" />

All the resources have been successfully deployed.
<img width="415" height="217" alt="image" src="https://github.com/user-attachments/assets/9abd4d6c-fcab-49d1-a0f6-e824b1d4ae8c" />

Here you go!
<img width="343" height="207" alt="image" src="https://github.com/user-attachments/assets/f6e8f548-32e8-41d3-9c14-f56a716a8482" />

Terraform destroy:
<img width="415" height="239" alt="image" src="https://github.com/user-attachments/assets/d4bad11b-4dd7-4cc2-a6e4-afe2f02159ce" />



---------------------------------------------------------------------------------------------------------------------------------------------------------

### Project 4: Static Website Hosting on Amazon S3

- Hosted a static portfolio website using Amazon S3 Static Website Hosting.
- Configured bucket permissions and enabled public access for website hosting.
- Uploaded HTML, CSS, and image assets to the S3 bucket.
- Accessed the website using the S3 static website endpoint.
- Technologies: HTML, CSS, Amazon S3, AWS
- Repository: https://github.com/Derick-Roshan/Portfolio-website

Creating S3 Bucket
<img width="415" height="151" alt="image" src="https://github.com/user-attachments/assets/ac06c3a9-8279-4a4b-a576-0df173514d70" />

The Bucket name should be unique because is Global.
<img width="415" height="146" alt="image" src="https://github.com/user-attachments/assets/95577b3f-e3ef-4371-9396-31d942b5d3b9" />

We need to enable the ACL enable to make bucket public.
<img width="416" height="109" alt="image" src="https://github.com/user-attachments/assets/6ee23d19-c9dd-44d7-a704-0b1c89adad7d" />

I unchecked the “Block all public access” and need to accept the acknowledgment.
<img width="416" height="156" alt="image" src="https://github.com/user-attachments/assets/9fd7c1dd-6a7f-466f-8dfb-caaaf5aa4f92" />

And click on “Create bucket”
<img width="415" height="62" alt="image" src="https://github.com/user-attachments/assets/022f1518-86a1-45ce-ad3c-f9a2f6f6ea70" />

After creating the bucket we need to upload the HTML & CSS all the website files.  That files are known as “Objects” in S3.
We can do this by drag and drop.
<img width="415" height="149" alt="image" src="https://github.com/user-attachments/assets/95ded14a-6528-4ffb-a271-ececb9501b4e" />

And click on upload. 
<img width="415" height="116" alt="image" src="https://github.com/user-attachments/assets/1d9abd00-7f45-486f-bde1-cd2d72711e8f" />

You can see files have been uploaded.
<img width="414" height="132" alt="image" src="https://github.com/user-attachments/assets/db5df78c-224a-4992-af64-a5bad88664ce" />

Click on “Properties” and search for “Static web hosting” click on edit and enable it.
<img width="415" height="79" alt="image" src="https://github.com/user-attachments/assets/c8f2354b-03f3-479f-a603-1679c6d7ed3a" />
<img width="416" height="147" alt="image" src="https://github.com/user-attachments/assets/3122e79a-5b48-457f-b0b8-4a410ea99cfa" />

Go inside the “index.html”
<img width="415" height="105" alt="image" src="https://github.com/user-attachments/assets/d592c7d6-bc42-4b57-adbf-ea93af466d8f" />

Go to “Permissions” and click on Edit.
<img width="415" height="151" alt="image" src="https://github.com/user-attachments/assets/fa1f2b79-b016-42a1-afdb-35d8d5928946" />

Enable the read for Everyone (public access), and grant the access.
<img width="415" height="174" alt="image" src="https://github.com/user-attachments/assets/bad9ddb4-3d5c-47e8-9aa3-2bc5d0fe448e" />

Copy the URL and past it in a new tab!
<img width="415" height="164" alt="image" src="https://github.com/user-attachments/assets/32c5e445-fdbd-4165-b016-45bf7306a74e" />

You can see that CSS files are not integrated, to do that.
<img width="415" height="301" alt="image" src="https://github.com/user-attachments/assets/8dece323-af2a-4daa-b5a9-07ab51305ac5" />

Go inside the Bucket and select all.
<img width="415" height="144" alt="image" src="https://github.com/user-attachments/assets/cc4c83c9-778c-450f-a22e-fa96b082e532" />

Click on “Actions” and click on “Make public using ACL”
<img width="416" height="295" alt="image" src="https://github.com/user-attachments/assets/b5cad00f-157e-4e86-98ac-efe50272e64d" />

Click on “Make public”
<img width="415" height="73" alt="image" src="https://github.com/user-attachments/assets/d1c3a118-43f4-455f-b900-7f6322d7678c" />

Here you go!
<img width="416" height="180" alt="image" src="https://github.com/user-attachments/assets/d77d1e73-9397-4047-93bf-6213571256e8" />



