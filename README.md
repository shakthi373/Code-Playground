# Code_Playground
Its an Academic project
Features
1. User Registration
2. User Login
3. Admin Login
4. Admin panel
5. Report Generation
6. Write or develop the code that powers the web
7. Run C and C++ code
8. Give quiz exam
9. Sorting algorithms visualizer to see how sorting works

Frontend Technology
1. HTML
2. CSS
3. JavaScript
4. Bootstrap
5. jQuery

Backend Technology
1. PHP
2. MySQL

Tools Used
As for the functional requirements, we have indicated the following: 
1) Development tools, Visual Studio Code, and a sustainable environment for 
development. 
2) The Apache web server for deploying the application and establishing 
relational-database connections. 
3) Different Compilers which will compile code of different types of programming 
languages.

# Installation setup

1. Run XAMPP.
2. Creat a database called code_playground
3. Import given sql file into that database (File Locaton: Code_Playground\Database)
4. Copy and paste the Code_Playground folder to C:\xampp\htdocs
5. Go to a browser and type http://localhost/code_playground/




• In Code_Playground folder goto---> Code_Playground>main_web>IDE playground>compilers>c and cpp and cpp11

  path is C:\Program Files\CodeBlocks\MinGW\bin (In my computer case).

  IF YOU HAVE A DIFFERENT PATH FOR C/C++ COMPILER THEN CHANGE THE PATH IN THE FILE(Code_Playground>main_web>IDE playground>compilers>c.php and cpp.php and   cpp11.php)


• There is a "web test.txt" file contian some demo code to check web playground is working or not. (Code_Playground\main_web\web playground)
  There is sample C/C++ demo code folder. (Code_Playground\main_web\IDE playground\code) 

• Admin: user name: admin, password: 12345
  If you want to add another admin than write MySQL code to create new admin or use XAMPP GUI. Use the bcrypt algorithm for password.
  Example: Password = 12345, than Enter "$2y$10$azd9hwV9elAXc598gv25P.hZ0fw8j2QlKbU7Q/ddOjuBg349SoQZm" which is the bcrypt of 12345. You can find bcrypt   hash generator online.

• User: user name: Mehedi Hasan, Password: 12345
