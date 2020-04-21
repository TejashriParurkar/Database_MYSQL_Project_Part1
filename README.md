Database_MYSQL_Project_Part1
Steps to run PAPER_REVIEWS database using given .sql file(paper_reviews.sql):

1. Download Mysql: https://dev.mysql.com/doc/mysql-getting-started/en/
1. create a database naming test (you can give any name you want): CREATE DATABASE test;
1. Check to see if it's empty: USE test SHOW TABLES;
1. Now, we need to import paper_reviews.sql file to mysql.
   - Open cmd (run in administration mode just to avoid "Access denied")
   - Now, navigate where you installed mysql. e.g C:\Program Files\MySQL\MySQL Server 8.0\bin in cmd, type 
   - cd "" (cd "C:\Program Files\MySQL\MySQL Server 8.0\bin") This will change it's directory. 
   - mysql -u root -p < (mysql -u root -p test < C:\Users\tpage\Desktop\paper_reviews.sql)
   - Now the terminal will ask you password.
   - Enter the password you set while installing mysql. [ The file has successfully imported ]
1. Now, let's open mysql command line Now check
