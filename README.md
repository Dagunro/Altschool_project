# A Dynamic landing page

A simple and elegant personal portfolio website template built with HTML and CSS.

## AWS Server setup

- I searched for the EC2 Instance page on the AWS management console.
- Clicked on the Launch instance button to set up a new instance
- Picked an instance name, Chose an amazon linux AMI image
- Selected a t3.micro as my instance type and created a new KEY PAIR
- Under the network settings, i allowed traffic from SSH, HTTP and HTTPS
- I then lauched my EC2 instance.
- After the setup, I clicked the connect button and on the SSH Client tab, copied the ssh code to be used with my SSH Client
- On my local terminal, i changed the public key permission to make it remains private using "chmod 400 .pem"  file.
- on my SSH client, i navigated to the location of my ec2 key  and pasted the code i copied from the SSH Client tab on the AWS EC2.

## Nginx Server Setup

1. Installed nginx on the server using "Sudo yum install nginx"
2. Started the server with the "Sudo systemctl start nginx" command.
3. Enabled the server to start immeediately with the "sudo systemctl enable nginx" command
4. Check for successfully installation using the public DNS provided by AWS.
5. After confirmation, i navigated to the html folder using /usr/share/nginx/html
6. Compressed the folder to a zip file where the website files are located and uploaded to the remote server.

## Deploying to the server

1. Moved the file from the remote server to the html folder.
2. Unzipped the folder 
3. Move it from the website folder into the html folder
4. Connect using the Public DNS.

## PUBLIC DNS
- [Link to the website](51.20.2.253)

Voila...................... Find the below screenshot


![Screenshot from 2025-06-15 22-49-23](https://github.com/user-attachments/assets/4ecd3855-1177-4dc9-b18b-767ae6feacf8)


![Screenshot from 2025-06-15 22-51-12](https://github.com/user-attachments/assets/6fb5ea9b-5aec-4943-8462-b6e0ded26590)




