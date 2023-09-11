# SSL-Certificates
For creating SSL certs on ubuntu


If we want to generate ssl certificate on amny server then it is for to generate csr file it could be happen when we install openssl
on server.
certificate authority for Service provider  Godaddy or semantic  



openssl req -new -newkey rsa:2048 -keyout technical-safar.club.key -out technical-safar.club.crt -days 365 -nodes

*****it will generate keyoutput of crt file (csr file)and a private-key file which we need  in configure and by crt file only it will give you certificate of SSL by any ssl service provider****

### By this site you can get SSl cetificate via crt file 

""https://www.acmetek.in/free-ssl-certificate ""

####it is the main file which we have to configure for ssl certificate

cd /etc/apache2/sites-available/default-ssl.conf
