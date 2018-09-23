DOCKER TASK FOLDER


* steps-of-LEMP-project.docx -> this dile contains all steps performed to complete the task

*   STEP BY STEP PROJECT .docx -> steps and screen shots of each steps

*   logs folder -> contains nginx-error log and inginx-access log

*   nginx folder -> contains default file -> contains server configuration of nginx

*   public folder -> contains index.php file -> which is hosted on nginx server and display the records in the database

*   docker compose.yml -> this is the file in which installation of LEMP project and images are pulled from docker hub. and deploy the   .     index.php (here named with connectivity with database.php)
  
----------------------------------------------------------------------------------------------------------------------------------------

ANSIBLE AUTOMATION


*   ansible lemp playbook.yml ->  this is automation script for automate the deployment for LEMP project and also configure the      .         nginx,php,mysql

* nginx.conf -> this file is passed into the nginx by using copy module

* index.php ->  this is the file which is deploy on the server by nginx which contains database and php connectivity code

NOTE: Ansible step by step screen shots are not taken due to office schedule and work load I couldn't get enough time to explain details of Ansible and make documents for it. like DOCKER TASK. 
----------------------------------------------------------------------------------------------------------------------------------







 
 
 
 
