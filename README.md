i. The IP address and SSH port so your server can be accessed by the reviewer.
IP: 35.180.158.82 SSH-Port: 2200

ii. The complete URL to your hosted web application.
http://35.180.158.82:5000/

iii. A summary of software you installed and configuration changes made.
- changed the ssh port 
- installed mandatory files for running the application
- Flask
- oauth2client
- requests
iv. A list of any third-party resources you made use of to complete this project. 
- none 


Notes:
in cmd: ssh grader@35.180.158.82 -p 2200 -i ~/.ssh/LinuxCourse1

password for grader: none
(yes the password is none spelled out, there IS a password)

To start the application:
Login as grader
cd ItemCatalogProject
python project.py
then open your browser and go to 35.180.158.82:5000
