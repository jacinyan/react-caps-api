## Description

Server runs on `PORT=9000` by default. 

For accessing users resources, simply create a users.json file at root level following the format: 

```json
{
    "users": [
        {
            "id": 1,
            "username": "admin",
            "email": "admin@test.com",
            "password": "password",
            "role": 1
        },
        {
            "id": 2,
            "email": "user@test.com",
            "password": "password",
            "username": "user",
            "role": 0
        }
    ]
}
```