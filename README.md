# How to use
1. Clone my repository
   
```bash

2. mkdir ssl
3. cd ssl
4. openssl req -x509 -nodes -days 365 -newkey rsa:2048 \ 
-keyout mistletoe.key -out mistletoe.crt \ 
-subj "/C=US/ST=State/L=City/O=Organization/OU=IT/CN=mistletoe"
5. cd -
6. docker compose up
7. Check your ip address, there you can find wordpress:

```

![image](https://github.com/user-attachments/assets/23d29588-cff3-4c32-8594-de5abe617aa4)

