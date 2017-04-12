# assessment-app
A RESTful APL spring-boot application for Apex Systems

This project is an attempt at creating a web services application using Java Spring Boot, AOP, etc. The project is able to upload local files. It can also save the data of a BankMember object that I've created within a storage system. A BankMember consists of two ints and two strings. A JSON example follows below:

{ "id":1,
"firstName":"Jennifer",
"lastName":"Anwarye",
"balance":"20000"
}

-- The initial localhost/8080 page is where the file uploading takes place. 
-- Files can be dowloaded by appending /files/{filename} to the URI.
-- GET, PUT and POST can be used at localhost/8080/bankMembers/
-- GET and DELETE can be used at localhost/8080/bankMembers/{id}
