# Endpoints

## Overview
* [Authenticate](#authenticate)

### Authenticate
#### GET `https://chats.user-agent.cc/token/:tokenID`
 ```json

   /* Response */  


   // if success, status 200
     {
        "authState": true
     }

   // if miss token, status 500

     {
        "authState": false
     }

 ```

## 
