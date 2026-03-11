TAMPILAN WEB
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/36b39dfb-a226-4954-b45c-c0a177d84ff6" />

GET

Get All User - Path '/api/users'

Response

{
    "data": [
        {
            "age": 22,
            "id": "4ec5b6ef-a7e7-4e51-b12e-8531d6431c22",
            "name": "faradilla azzahra"
        },
        {
            "age": 21,
            "id": "935aa789-10fe-4d94-89d1-1f2c7012304c",
            "name": "ahmad ajo pratama"
        }
    ],
    "status": "success"
}


Get User by Id - Path '/api/users/{id}'


{
    "data": {
        "age": 21,
        "id": "935aa789-10fe-4d94-89d1-1f2c7012304c",
        "name": "ahmad ajo pratama"
    },
    "status": "success"
}


POST

Path '/api/user'

Response

{
    "data": {
        "age": 22,
        "id": "ee4f6dff-f9e3-4258-b941-20420e716f46",
        "name": "JOJO"
    },
    "status": "success"
}

PUT

Path '/api/users/{id}'

Response

{
    "data": {
        "age": 22,
        "id": "ee4f6dff-f9e3-4258-b941-20420e716f46",
        "name": "JOJO PUPU"
    },
    "status": "success"
}

DELETE

Path '/api/users/{id}'

Response

{
    "status": "success delete user with id ee4f6dff-f9e3-4258-b941-20420e716f46"
}
















