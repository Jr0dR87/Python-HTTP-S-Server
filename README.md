# Python-HTTP-S-Server
Simple HTTPS Python Web Sever

I was working on the HTB Academy Advanced XSS and CSRF Exploitation course and it uses a HTTPS server to do the lab. The issue I had was the course uses a script for Python > 3.12. I modded the script to use Python 3.12 to run. This is nothing super fancy, but maybe it will help someone down the road in one way or another. <3

## OpenSSL Snippet to make server.pem
openssl req -new -x509 -keyout server.pem -out server.pem -days 365 -nodes
