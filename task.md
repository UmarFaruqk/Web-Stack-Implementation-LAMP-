# 1. WEB STACK IMPLEMENTATION (LAMP)

What is a Web Stack Implementation? - A web stack is the collection of software used for web development that incorporates, at a minimum, an operating system (OS), a programming language, database software and a web server.

2. # Tools you need:
   -VS code
   - AWS Account (To create your Instance) 
   - Windows Terminal (Installing Apache, Updating firewal, installing mysql, Apache, creating virtual host on the website using Apache and Enable PHP on the website)
   - GitHub (Creating a Repo)
  
3. # Step By Step Procedure:
   1.  *Amazon Web Service (AWS)*: Is the biggest service provider and it offers a free tier account that we leverged for our project.
   - Register a new AWS account 
   - Select your preferred region and launch an EC2 instance of t3.micro family with Ubuntu server 24.04 LTS(HVM)
   - save your key (.pem file) and do not share with anyone 
   - Use both putty and ssh protocol to establish connectivity between computers
   - now we use the pem key to connect our EC2 instance via ssh ![reference image](/pictures/picture1.PNG)
   - 
  2. *Windows Terminal*
     - Apache and Updating firewall: Is an open sours software available for free. it runs 67% of all webservers in the world. So we download it ![reference image](/picture/picture2.PNG)
     - So we open TCP port 80 on oue EC2 which is the default port that web browsers use to access web pages 
     - The we use the curl command to access our local host ![reference image](/image/picture3) then we test our apache http server ![reference image](/image/picture4) 
     -  Install mysql ![reference image](/image/picture5)
     -  start the interactive script ![reference image](/image/picture6) and ![reference image](/image/picture7)
     -  Test if you are able to access mysql console ![reference image](/image/picture8) 
     -  Installing PHP ![reference image](/image/picture9)
     -  creating a virtual host for the website using apache we first create a directory then we assign ownership of the directory with the user finally we create and open a configuration file in apache's *sites available* ![reference image](/image/picture10) ![reference image](/image/picture11) ![reference image](/image/picture12)
     -  Now we use a2ensite and also a2dissite apache's default configuration then make sure it does not contain syntax error ![reference image](/image/picture14)
     -  The next step is to reload the apache ![reference image](/image/picture15)
     -  Enable PHP on the website ![reference image](/image/picture16) and ![reference image](/image/picture17)
  

  #With these step by step procedure I was able to create my web stack implementation (LAMP STACk)

  

