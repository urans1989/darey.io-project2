## WEB STACK IMPLEMENTATION (LEMP STACK)

### INSTALLING THE NGINX WEB SERVER
http://<Public-IP-Address>:80
  
![nginx-web-server](https://user-images.githubusercontent.com/102744118/173582663-06c3c0a9-e6d7-4738-b68a-b74fafcca1f2.png)
  
### INSTALLING MYSQL
   sudo mysql
  
![mysql-installation-nginx](https://user-images.githubusercontent.com/102744118/173583677-37a8c93d-23da-49b0-bff6-53249607790b.png)
  
### INSTALLING PHP
 sudo apt install php-fpm php-mysql
  

  ### CONFIGURING NGINX TO USE PHP PROCESSOR
  
  ![nginx-php-processor](https://user-images.githubusercontent.com/102744118/173611822-e0272807-1ace-49a5-a431-4635b335fe81.png)

  ### TESTING PHP WITH NGINX
  http://`server_domain_or_IP`/info.php
  
  ![testing-php-nginx](https://user-images.githubusercontent.com/102744118/173612503-c4284646-883c-4c1f-9856-5118bacca4c0.png)
  
  ### RETRIEVING DATA FROM MYSQL DATABASE WITH PHP
  #### mysql> SHOW DATABASES;
  
  ![msyl-databases](https://user-images.githubusercontent.com/102744118/173613055-efaef7a4-ce9b-4ebf-a12e-1661b91a44e3.png)
  
  
  #### create table 
  ![created-table-mysql-nginx](https://user-images.githubusercontent.com/102744118/173613416-4b126684-f471-4d0d-8fdc-aeddbbd643a0.png)
  
  
  #### A toto list app
  http://<Public_domain_or_IP>/todo_list.php
  
  ![todolist-info php](https://user-images.githubusercontent.com/102744118/173614938-3c64337a-95ff-4d16-b7e7-b2f7b710df4c.png)

  
