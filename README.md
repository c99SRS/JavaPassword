# JavaPassword

Here I am using Javax.crypto library  and java.security library for encoding password  to protect from external access .It will convert user entered password into Hash value .I am using Md5 and AES implementation .
When encrypt method calls from main method i am  passing password in plain text along with initialvector and secretkey . 
Initial vector should be 16 character . For providing more security and preventing from Dictionary attck and bruteforce attack 
we are passing secret key .  Using secret key it will encrypt as well as decrypt the password and generate hash value for the password , which is safe .
