# Login Registration Backend 

Complete login registration backend system using Spring Boot.

- [x] Spring Boot
- [x] Spring Security
- [x] Java Mail
- [x] Email verification with expiry
- [x] Spring Boot

## Diagram









### CURL
```
curl --location --request POST 'localhost:8080/api/v1/registration' \
--header 'Content-Type: application/json' \
--data-raw '{
    "firstName": "Shavaiz",
    "lastName": "Malik",
    "email": "shavayiz463@gmail.com",
    "password": "password"
}'
```
