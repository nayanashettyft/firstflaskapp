# firstflaskapp

```
virtualenv -p python3 venv
. venv/bin/activate
pip install flask
pip install flask-mysqldb
pip install flask-WTF
pip install passlib
python app.py
```

#### MYSQL Setup
```
brew info mysql
brew install mysql
brew tap homebrew/services
brew services start mysql
brew services list
mysql -V
mysqladmin -u root password 'yourpassword'
mysql -uroot -pyourpassword
mysql> SHOW DATABASES;
mysql> CREATE DATABASE firstflaskapp;
mysql> USE firstflaskapp;
mysql> CREATE TABLE users(id INT(11) AUTO_INCREMENT PRIMARY KEY, name VARCHAR(100), email VARCHAR(100), username VARCHAR(30), password VARCHAR(100), register_date TIMESTAMP DEFAULT CURRENT_TIMESTAMP);
mysql> SHOW TABLES;
mysql> DESCRIBE users;
mysql> SELECT * FROM users;
```
