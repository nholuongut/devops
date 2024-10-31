### Features

- Create user on the specied linux server

Create user on the specied linux server.
-------------

**Script Name:** provide-access.sh
**Parameters to the Script:** 5
**Usage:** ./provide-access.sh -U login-user-name -K path-to-login-pem-key -I login-ip  -u user-to-be-created -k  "public-key-to-be-added-in-double-quotes"
***Where,*** 
```
        -K .pem key of the server on which a new user has be created
        -U UserName of the server on which a new user has be created
        -I IP of the server on which a new user has be created
        -u user to be created on the internal server
        -k public key string to be added shared by the user
```
**Note:**
`Pass Public Key in double quotes`

**e.g.**
`./provide-access.sh -U ubuntu -K /Users/nholuongut/Documents/nholuongut/access/nholuonguts.pem -I 192.168.134.100  -u nholuongut -k  "ssh-rsa xxxxxx key-name"`
