# CREATION IN WEB APPLICATION FOR TEST ENVIRONMENT

## AIM
 To Creation in Web Application for Test Environment.
   
## PROBLEM STATEMENT
 Creating a web application for a test environment is essential to provide developers and testers with a dedicated platform to simulate, test, and validate software functionalities. The challenge lies in building an easy-to-use, scalable, and efficient application that supports realistic testing scenarios, automates workflows, and ensures smooth collaboration while minimizing setup and maintenance efforts.
    
## ALGORITHM
# Step 1:
Launch an EC2 instance in AWS using an Amazon Linux 2 AMI with a Security Group allowing HTTP and SSH traffic.
# Step 2:
Connect to the instance using SSH and install a web server like Apache
# Step 3:
Create a simple HTML file in the server's default directory with basic content for testing.
# Step 4:
Access the instance's public IP in a browser to verify the HTML page is displayed.

## COMMANDS
# webserver
To install httpd:
```
yum install httpd -y
```
To enable and start httpd :
```
systemctl enable httpd
systemctl start httpd
```
Create a simple HTML page :
```
cd /var/www/html
```
test.php
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>MY FIRST PHP!</title>
</head>
</body>
</html>
```

## OUTPUT
### NAME: KAVINESH M
### REG NO: 212222230064
# TERMINAL
![image](https://github.com/user-attachments/assets/92d227f7-c6ec-4c36-8423-526e3ee6ea94)
![image](https://github.com/user-attachments/assets/7c3131bf-92fd-46c8-b41b-0a5316441b71)
![image](https://github.com/user-attachments/assets/b382bcf9-3dc0-4b62-9e45-9a2d911d691f)

# WEBPAGE

![image](https://github.com/user-attachments/assets/81e806f5-a6b3-406d-bb39-da9665197e4c)

## RESULT
Thus the web application for test environment has successfully been created and executed.
