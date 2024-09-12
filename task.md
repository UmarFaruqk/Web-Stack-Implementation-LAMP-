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
   - now we use the pem key to connect our EC2 instance via ssh ![reference image](/Pictures/Picture1.PNG)
   - 
  2. *Windows Terminal*
     - Apache and Updating firewall: Is an open sours software available for free. it runs 67% of all webservers in the world. So we download it ![reference image](/Pictures/Picture2.PNG)
     - So we open TCP port 80 on oue EC2 which is the default port that web browsers use to access web pages 
     - The we use the curl command to access our local host ![reference image](/Pictures/picture3) then we test our apache http server ![reference image](/Pictures/picture4.PNG) 
     -  Install mysql ![reference image](/Pictures/picture5.PNG)
     -  start the interactive script ![reference image](/Pictures/picture6.PNG) and ![reference image](/Pictures/picture7.PNG)
     -  Test if you are able to access mysql console ![reference image](/Pictures/picture8.PNG) 
     -  Installing PHP ![reference image](/Pictures/picture9.PNG)
     -  creating a virtual host for the website using apache we first create a directory then we assign ownership of the directory with the user finally we create and open a configuration file in apache's *sites available* ![reference image](/Pictures/picture10.PNG) ![reference image](/Pictures/picture11.PNG) ![reference image](/Pictures/picture12.PNG)
     -  Now we use a2ensite and also a2dissite apache's default configuration then make sure it does not contain syntax error ![reference image](/Pictures/picture14.PNG)
     -  The next step is to reload the apache ![reference image](/Pictures/picture15.PNG)
     -  Enable PHP on the website ![reference image](/Pictures/picture16.PNG) and ![reference image](/Pictures/picture17.PNG)
  

  #With these step by step procedure I was able to create my web stack implementation (LAMP STACk)

  

