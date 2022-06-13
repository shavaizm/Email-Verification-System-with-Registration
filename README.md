Email Verification System with Registration!

This is a full registration system with login and verification and it is implemented through Java and the Spring framework using SQL as a database. 

- [x] Spring Boot
- [x] Spring Security
- [x] Java Mail
- [x] Email verification with expiry
- [x] Spring Boot

## Diagram

<img width="799" alt="Screen Shot 2022-06-03 at 6 12 31 PM" src="https://user-images.githubusercontent.com/105877485/171962202-109d1c9b-0a05-4a5f-94b2-67e55b58b91c.png">



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
