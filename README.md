# # Linux Server Configuration
**by ٌReda Zerrougui**


 ## Project  Description:

This is the sixth project for the Udacity Full Stack Nanodegree., called " Linux Server Configuration "
The Linux Server Configuration project  involves taking a baseline installation of Linux on a virtual machine and preparing it to host web applications. This includes installing updates, securing the server from attacks, and installing / configuring web and database servers.

## # Server Information

-  IP address: 18.185.113.206
- URL : http://bookscatalog.tk/
- To connect: ssh -i id_rsa grader@18.185.113.206 -p 2200



## summary of software installed and configuration changes made
1.  Set up Ubuntu server on AWS Lightsail
2.  Added a new user "grader" and gave sudo permission
3.  Set up ssh-key using a local computer (Macbook)
4.  Added public key to the server
5.  Set up a firewall in the server and in the AWS Lightsail to only allow incoming connections with SSH-key
6.  Configured local timezone to UTC
7.  Installed Apache2, mod_wsgi, and PostgreSQL applications
8.  Created a database with limited access permissions
9.  Installed Git
10.  Clone the project [Item-Catalog](https://github.com/redateur13/Item-Catalog) from Github
11.  Installed libraries, such as flask, sqlalchemy, psycopg2, oauth2client, httplib2, requests
12.  Made and configure the WSGI file 
13.  Changed the path of databases 
14.  Executed a python file`` __init__.py ``to launch the app
15. set up a domain name  http://bookscatalog.tk/


## Resources Used
[https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps](https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps)
[https://www.digitalocean.com/community/tutorials/how-to-install-and-use-postgresql-on-ubuntu-16-04](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-postgresql-on-ubuntu-16-04)

 ## Licence

The MIT License ([MIT](https://choosealicense.com/licenses/mit/#))
Copyright (c) [2018] [Reda Zerrougui]
