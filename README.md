# Secure-ish-login-system-with-PHP-and-mysql
This is a web login system I developed that compares submitted usernames and passwords to database records to check if they are valid. Firstly it will try and find the given username on the name section of the Users table. If it finds one or more names matching the one submitted it will then check if the entered password matches one of these accounts, if so it will display a succesfull login screen, if not an login failed message is shown. Currently this does not support hashing but I may change this later.

