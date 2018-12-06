# Linux Server Configuration

## Things =>
### URL
  http://ec2-13-127-215-124.ap-south-1.compute.amazonaws.com
  * if you want to login with google make sure to go throgh the url not the ip.
  
### IP address
  http://13.127.215.124/
  
  
### Port  
  2200
  
  
  
## Steps to make a similar project =>
1. Smile 
2. Create an account here >> https://lightsail.aws.amazon.com
    * it make takes 24hour to activate your account.
3. Create an (Ubuntu 16.04) instance.
    * Wait till it says running.
4. ssh to the server using the SSH key
    * SSH key can be found in account SSH keys.
5. Create a different SSH key in your machine.
6. In server, create new user (grader).
7. Give it sudo access.
8. In /home/grader/.ssh/authorized_keys paste the public key created in 5.
9. Configue ports 2200, 80 and 123.
10. Enable firewall.
11. Install apache2, WSGI module and Postgresql.
12. Configure Apache to run a flask app and install the needed modules.
13. Install and configure Postgre SQL.
14. Visit your server IP address.
15. Enjoy.


## Resourses =>
1. PostgreSQL Documentation
  https://www.postgresql.org/docs/
  
2. Apache Documentation
  https://httpd.apache.org/docs/
