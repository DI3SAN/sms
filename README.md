# Stock Management System (SMS)

Installation guide

Before we start please install these tools
Git - https://git-scm.com/
XAMPP - https://www.apachefriends.org/index.html
** Ignore if you already installed these

1. After installation, clone this https://github.com/DietherKenz/sms in your htdocs folder in xampp folder.
2. for cloning:
3. open cmd then go to local disk c directory then direct it to htdocs folder
![image](https://user-images.githubusercontent.com/23739496/136080453-5fee6b92-5ca4-4cc1-b5f8-7a35a64f994f.png)
4. It should look like this
5. C:\xampp\htdocs\
6. after that add this cmd line git clone https://github.com/DietherKenz/sms.git
7. it should look like this C:\xampp\htdocs\git clone https://github.com/DietherKenz/sms.git 
![image](https://user-images.githubusercontent.com/23739496/136080488-88ceea20-0854-46d8-ad81-08f2f3625196.png)
8. then enter
9. After cloning
10. Run XAMPP
11. then click the start button of Apache and MySQL
![image](https://user-images.githubusercontent.com/23739496/136080546-9bf4945c-6c86-41b9-b639-e68663aadbdb.png)
12. then go to your chrowser (chrome or mozilla fox or edge) type this http://localhost/phpmyadmin
![image](https://user-images.githubusercontent.com/23739496/136080651-b0faa5c0-1462-4e46-ba91-04d04078a771.png)
13. then in PhpMyAdmin page, click the SQL tab location in the middle top screen then run this: "CREATE DATABASE sms;" with out the double quotation marks
![image](https://user-images.githubusercontent.com/23739496/136080816-a1c59a78-ba68-433c-8b39-f050d36b9e40.png)
14. after creating database, import the sms.sql file in sms folder in htdocs we cloned. 
![image](https://user-images.githubusercontent.com/23739496/136080055-3bc926b2-649a-46a1-94fd-11e24c16678f.png)
15. after importing, run in another tab in your browser this link: http://localhost/sms/index.php
16. It should look like this
![image](https://user-images.githubusercontent.com/23739496/136081162-ed6ca3c3-12f3-46ca-8069-a540fce39b65.png)
17. That's all. Enjoy Keep safe!
