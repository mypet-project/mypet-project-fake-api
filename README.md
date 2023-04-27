MyPets Api Resquisições

Endpoints

Cadastro
`POST http://localhost:3000/users`

```
 {
   "name":"Fulano1",
   "email": "A1@mail.com",
   "password": "A1@mail.com",
   "borndate": "25/08/92",          
 }
```

Login
`POST http://localhost:3000/users`

```
"users":
        {
            "name":"Fulano1",
            "email": "A1@mail.com",
            "password": "A1@mail.com",
            "borndate": "25/08/92",            
        }
```  

Usuários 
`GET http://localhost:3000/users`

```
"users": 
        {
            "id": 1,
            "name":"",
            "email": "A1@mail.com",
            "password": "A1@mail.com",
            "borndate": "25/08/92",
        }
 ```      

Informações dos pets

PETS
`GET http://localhost:3000/pets`

```
"pets": 
[
        {
            "id": 1,
            "name": "Luluzinho da pomeraniazinha",
            "img": "https://images.pexels.com/photos/8473518/pexels-photo-8473518.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1",
            "category": "Cachorro",
            "description": "oia q lindinhu meu luluzinho da pomeraniazinha",
            "adoption": "Não"
        },
        {
            "id": 2,
            "name": "Husky siberiano",
            "img": "https://imgur.com/L0wKu8G",
            "category": "Cachorro",
            "description": "Ele gosta muito de brincar no gelo.",
            "adoption": "Sim"
        }
    ]
```
