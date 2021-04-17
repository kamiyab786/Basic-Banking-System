# Basic-Banking_system

**Sparks Foundation Internship Project:** ***Basic Banking System***

A Web Application used to transfer money between multiple users (Project contains 10 dummy users). A dummy user can also be created.

**Stack used:**
- Front-end : HTML, CSS, Bootstrap, AngularJS
- Back-end : NodeJs , ExpressJs ,MongoDB

Database contains two Tables- Customers Table & Transaction History Table

Customers table have basic fields such as name, email & current balance.
Transaction History table records all transfers happened along with their time.
Flow of the Website: Home Page > View all Users > Select and View one User > Transfer Money > Select reciever > View all Users > View Transfer History.

**How To Run Project:-**

 1. Install NodeJs
 2. Install MongoDB And MongoDB Compass
    - Connect MongoDB Compass with localhost
    - Create Database with Name "myproject"
    - Collection Name "sparkbank"
    - Add Dummy data with field  
      - "name" dataType : String 
      - "email" dataType : String 
      - "balance" dataType : Int32
 3. In Project File Open Terminal/CMD/PowerShell
 4. type npm init
 5. type npm install mongoose
 6. type npm install express
 7. type node server.js
 8. Open Browser Use This Link to Run Project 'http://localhost:2800'.

![1](https://user-images.githubusercontent.com/50388943/115108780-eff6ca00-9f8f-11eb-8aac-b8147d9abb33.png)
![2](https://user-images.githubusercontent.com/50388943/115108781-f127f700-9f8f-11eb-98bf-44cccdf10a15.png)
![5](https://user-images.githubusercontent.com/50388943/115108785-f84f0500-9f8f-11eb-9d7a-4e5cfd269349.png)
![3](https://user-images.githubusercontent.com/50388943/115108792-000ea980-9f90-11eb-8dde-ad6c75e87ab3.png)
![4](https://user-images.githubusercontent.com/50388943/115108795-013fd680-9f90-11eb-80c6-37705874809b.png)
