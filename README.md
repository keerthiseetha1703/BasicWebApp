# BasicWebApp
A basic Flask WebApp deployed on EC2

This is a basic web app built using Flask framework in python.
Web App has two pages HOME and ABOUT with navigation between them.
The CSS file defines the way the text looks.

Deployement on EC2 instance :
Create an AWS account.
Launch an EC2 instance with all default settings.
ssh into EC2 from the local.
Transfer the files from local into EC2 folder via scp. First move the files into tmp , then into /otp/ to be on safer side.
Make sure that the main python code has the host = 0.0.0.0 and port =80.
Run the python project.
Copy the IPv4 address of EC2 instnace and put it in the browser.
The WebApp is up and running.
