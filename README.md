# Node JS With JSON Server and JWT

## **Configuration This Project**

- Run `npm install`
- Run `npm run mock:api`
- Open Postman to test API with JWT

You can login/register by sending a POST request to

```
POST http://localhost:4000/auth/login
```

with the following data

```
{
  "email": "admin@email.com",
  "password":"secret"
}
```

You should receive an access token with the following format

```
{
   "access_token": "<ACCESS_TOKEN>"
}
```

You should send this authorization with any request to the protected endpoints

```
Authorization: Bearer <ACCESS_TOKEN>
```
