![PngItem_1369730](https://user-images.githubusercontent.com/62517615/138221269-aaad865a-6472-4067-9b0a-55b664f6bccd.png)
<img height="85" src="https://user-images.githubusercontent.com/62517615/138226039-233bf103-7ce2-4692-8549-242980da9a48.png" width="85"/>
### <img height="8" src="https://user-images.githubusercontent.com/62517615/138225868-0e00d4e5-14d3-4c96-8856-754cd9da1c6b.png" width="8"/>   **Run online version - deployment on Heroku**
[https://my-taxi-service.herokuapp.com/login](https://my-taxi-service.herokuapp.com/login)

### **Taxi Service Web Application**  
It's a taxi service web application, which I created to show my skills in Java, OOP, SOLID, DI, RDBMS, 
JDBC, WEB. 

### <img height="8" src="https://user-images.githubusercontent.com/62517615/138225868-0e00d4e5-14d3-4c96-8856-754cd9da1c6b.png" width="8"/> **Features provided by the application for registered users**
1. User(driver) can create new car or manufacturer
2. Add driver to a specific car
3. View all drivers, cars and manufacturers
4. View all cars by logged-in user
5. Delete car, driver or manufacturer

### <img height="8" src="https://user-images.githubusercontent.com/62517615/138225868-0e00d4e5-14d3-4c96-8856-754cd9da1c6b.png" width="8"/>    **Technologies**
1. Java 11
2. Maven
3. MySQL
4. JDBC
5. Javax servlet API
6. JSTL
7. JSP
8. Tomcat 9.0.54 (to run app locally)

### <img height="8" src="https://user-images.githubusercontent.com/62517615/138225868-0e00d4e5-14d3-4c96-8856-754cd9da1c6b.png" width="8"/>     **How to run this application** 
1. Install MySQL
2. Install Tomcat 9.0.54 version. Link -> [https://tomcat.apache.org/download-90.cgi](https://tomcat.apache.org/download-90.cgi)
3. Fork this project to your repository
4. Clone it using one of the "Code" options, which is more suitable for you
5. In resources directory you can find init_db.sql file. Use it to initialize you database
6. Add some data to DB
7. Go to the ConnectionUtil class located in src/main/java/mate/util and add your url to DB, login, password and JDBC driver there.
   (Be careful with adding URL. You should add a Timezone to it too)
8. Configure your Tomcat. (P.S. Your application context needs to be as "/")
9. Run this project using Tomcat's local server

![PngItem_1369730](https://user-images.githubusercontent.com/62517615/138221269-aaad865a-6472-4067-9b0a-55b664f6bccd.png)
