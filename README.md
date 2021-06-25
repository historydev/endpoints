# Endpoints

## Overview
* [Authenticate](#authenticate)
* [ManagersData](#managersdata)

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

### ManagersData
#### POST `/managers`
  ```json

     {

        "id": 1,
        "status": true,
        "name": "Света Щепина",
        "email": "nafullin@gmail.com",
        "position": "Отдел продаж",
        "openAuthUrl": "https://chats.user-agent.cc/?dialogs=D6546sd5034!-*/72134*&%$msddsaSD",
        "openAuthUrlStatus": true,
        "telegramAuthUrl": "https://chats.user-agent.cc/?dialogs=D6546sd5034!-*/72134*&%$msddsaSD",
        "telegramAuthUrlStatus": true,
        "isActive": true,
        "openAuthUrlUpdater": true,
        "telegramAuthUrlUpdater": true,
        "telegramPhone": "88003336655",
        "activeBots": "kukabot, supportbot, chekakbot",
        "classes": "запуск, все",
        "steps": "Запуск: Ожидание доплаты, все",
        "groups": "все, отдел запуска",
        "fields": { "РОП": "Маша", "МОП": "Оля" },
        "responsible": true,
        "outgoinMessages": "UTC TIME",
        "incomingMessages": "UTC TIME",
        "workingTime": "UTC TIME",
        "authSessions": 2,
        "dayAnswerDelay": "1600s",
        "monthAnswerDelay": "65428s",
        "isWork": true

     }

  ```
