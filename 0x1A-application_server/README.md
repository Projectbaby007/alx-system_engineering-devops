0x1A. Application server
DevOps
SysAdmin
 By: Sylvain Kalache, co-founder at Holberton School
 Weight: 1
 Project will start Jun 13, 2023 6:00 AM, must end by Jun 16, 2023 6:00 AM
 Checker will be released at Jun 15, 2023 4:48 AM
 An auto review will be launched at the deadline
Concepts
For this project, we expect you to look at these concepts:

Web Server
Server
Web stack debugging

https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2018/9/c7d1ed0a2e10d1b4e9b3.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230613%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230613T163214Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=df6604d7db1205a4cc82d91b5e5c01aac98f95cdaacb13a465571ddde47e503d

Background Context


Your web infrastructure is already serving web pages via Nginx that you installed in your first web stack project. While a web server can also serve dynamic content, this task is usually given to an application server. In this project you will add this piece to your infrastructure, plug it to your Nginx and make is serve your Airbnb clone project.

Resources
Read or watch:

Application server vs web server
How to Serve a Flask Application with Gunicorn and Nginx on Ubuntu 16.04 (As mentioned in the video, do not install Gunicorn using virtualenv, just install everything globally)
Running Gunicorn
Be careful with the way Flask manages slash in route - strict_slashes
Upstart documentation
Requirements
General
A README.md file, at the root of the folder of the project, is mandatory
Everything Python-related must be done using python3
All config files must have comments
Bash Scripts
All your files will be interpreted on Ubuntu 16.04 LTS
All your files should end with a new line
All your Bash script files must be executable
Your Bash script must pass Shellcheck (version 0.3.7-5~ubuntu16.04.1 via apt-get) without any error
The first line of all your Bash scripts should be exactly #!/usr/bin/env bash
The second line of all your Bash scripts should be a comment explaining what is the script doing
Your servers
Name	Username	IP	State	
181321-web-01	ubuntu	100.25.19.78	running	
181321-web-02	ubuntu	54.160.113.81	running	
181321-lb-01	ubuntu	100.24.238.39	running	

