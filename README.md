# php_mail
This is a complex php script that takes a user's email, password and name and then encrypts the text using AES 128 encryption. The text is then added to an HTML code which is then sent to the user's email for email confirmation during user registration to confirm if the user owns the email. The code utilizes the PHP Mailer library for sending emails on port 25 of an active server using the SMTP protocol.