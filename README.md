# Cleaned_Documents
# Currently there are some codes for connecting databases through APIs in python...
Save some useful codes for reference in the future.

Probably many useful things can be found in the files.
Mostly data, model and algorithms ...
Or some skills??

Other comments on IristoMysql code:
One should construct the Iris_db and Iris_test user, grant the user permission firstly by the following commands in MySQL server by admin(root)

CREATE DATABASE Iris_db;

CREATE USER 'Iris_test'@'localhost' IDENTIFIED BY 'Iris_12345678';

GRANT ALL ON Iris_db.* TO 'Iris_test'@'localhost';

FLUSH PRIVILEGES;

...
