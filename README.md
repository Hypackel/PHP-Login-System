# MongoDB PHP Login System

This is A very basic Registration and Login System using PHP and MongoDB.

## Dependencies

![Bootstrap](https://img.shields.io/badge/Bootstrap-7952b3?style=for-the-badge&logo=Bootstrap&logoColor=white)

Please note the following:

1. This system conists of a Registration page, to register new users, a Login page, for registered users.

2. A home page once a user logs in.

3. It also contains __register_action__ and __login_action__ to handle the data from register and login page respectively.

4. It has page access restrictions imposed using session such that a logged in user cannot access login or registration page and a user who is not logged in cannot access the home page.

5. It uses hashing to store passwords. And the BCRYPT encryption method is used to encrypt and store the passwords as opposed to the md5 and sha1 encryptions.

6. It consists of a seperate library file which contains the functions used in the system.

7. It was made with learning in mind and I'm open to all improvements that can be made to the system.

8. Feel free to use it as you please.

9. In __Connection.php__ You will need to fill in your mongodb connection string so it can connect to the server.
