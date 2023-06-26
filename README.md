# JS_4.4.9
JS_4.4.9

Registration:
query:
method: post,
url: https://blog.kata.academy/api/users,
json: {"user":{"username":"VladimirSazanakov","email":"sazanakov@inbox.ru","password":"test123"}}

Response:
{
    "user": {
        "username": "vladimirsazanakov",
        "email": "sazanakov@inbox.ru",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY0OTlkMWRmNjBjNjc1MWIwMGI3ODllZCIsInVzZXJuYW1lIjoidmxhZGltaXJzYXphbmFrb3YiLCJleHAiOjE2OTI5ODYzMzYsImlhdCI6MTY4NzgwMjMzNn0.LNhtes2rKhUQlNd7k2T_nP7gR6uZq-N32UC7oUwCVOk"
    }
}

Authentification:

query:
method: post,
url: https://blog.kata.academy/api/users/login
json: {"user":{"email":"sazanakov@inbox.ru","password":"test123"}}

Response:

{
    "user": {
        "username": "vladimirsazanakov",
        "email": "sazanakov@inbox.ru",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY0OTlkMWRmNjBjNjc1MWIwMGI3ODllZCIsInVzZXJuYW1lIjoidmxhZGltaXJzYXphbmFrb3YiLCJleHAiOjE2OTI5ODY2MjYsImlhdCI6MTY4NzgwMjYyNn0.lkR1_S4shhr5ZegqE_tLiCLnoiMEvSHSTFxxCCJIM44"
    }
}

Get Current User:
query: 
method: get,
url: https://blog.kata.academy/api/user,
auth bearer token:eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY0OTlkMWRmNjBjNjc1MWIwMGI3ODllZCIsInVzZXJuYW1lIjoidmxhZGltaXJzYXphbmFrb3YiLCJleHAiOjE2OTI5ODY2MjYsImlhdCI6MTY4NzgwMjYyNn0.lkR1_S4shhr5ZegqE_tLiCLnoiMEvSHSTFxxCCJIM44 

Response:

{
    "user": {
        "username": "vladimirsazanakov",
        "email": "sazanakov@inbox.ru",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY0OTlkMWRmNjBjNjc1MWIwMGI3ODllZCIsInVzZXJuYW1lIjoidmxhZGltaXJzYXphbmFrb3YiLCJleHAiOjE2OTI5ODc2NTYsImlhdCI6MTY4NzgwMzY1Nn0.b34Dub0XEs8UoOKor6-Yh5EUQc6d1pKRZXECyGopVGA"
    }
}




