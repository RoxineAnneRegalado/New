1. sudo apt update && sudo apt upgrade -y
2. sudo apt install apache2 -y
3. sudo systemctl enable apache2
4. sudo systemctl start apache2
5. sudo apt install mysql-server -y
6. sudo mysql_secure_installation

7. sudo mysql -u root -p
8. pic

9. sudo apt install -y phpmyadmin

10. /var/www/html$ cd /var/www/html
      /var/www/html$ sudo git clone https://github.com/RoxineAnneRegalado/moviess.git

11. sudo chown -R www-data:www-data /var/www/html/moviess
12. sudo chmod -R 755 /var/www/html/moviess

Sudo systemctl start mysql 
 
13. Create database movies_data;
14. sudo mysql -u root -p 
15. CREATE USER 'adminroxine'@'localhost' IDENTIFIED BY '@Adminroxine123!;

16. GRANT ALL PRIVILEGES ON movies_data.*TO 'adminroxine'@'localhost';
17. FLUSH PRIVILEGES;
18. exit
19. pic
20. pic
21. sudo ufw allow OpenSSH
22. sudo ufw allow 'Apache Full'
23. sudo ufw enable
24. picss
