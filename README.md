# Authentication Spring Security JWT 

This is the implement JWT Authentication using Spring Boot and Spring Security

# How to Use

## Prerequisites
You need to have the following installed
- [Java](https://www.java.com/en/download/)
- [Git](https://git-scm.com/downloads)

If you want to download the source code, follow the below steps :-

- Clone or download the project
- Open your IntelliJ IDE
- Select Open project and navigate to the location where you cloned the source code
- Run the AuthJwtApplication
- call these services:

### POST http://localhost:8080/api/auth/signup
Content-Type: application/json

{ 
    "email" : "p@a.com",
    "password" : "123"
}

### POST http://localhost:8080/api/auth/signin
Content-Type: application/json

{
    "email" : "p@a.com",
    "password" : "123"
}

### GET http://localhost:8080/api/user/info
Content-Type: application/json

Authorization: Bearer eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJVc2VyIERldGFpbHMiLCJpc3MiOiJZT1VSIEFQUExJQ0FUSU9OL1BST0pFQ1QvQ09NUEFOWSBOQU1FIiwiaWF0IjoxNjcxNzkxNjMzLCJlbWFpbCI6InBAZ21haWwuY29tIn0.pMbicUbLyStKbh4GQImgH4AX_wAYDMafUH4w2SH1uvg


