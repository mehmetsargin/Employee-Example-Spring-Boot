# Employee-Example-Spring-Boot
#Spring Boot and mySql used in this project. #I tried to develop a basic employee service. # Spring REST API Security is included in this project. 

Using GET Method
http://localhost:8080/api/employees >>> endpoint is giving all employees in database. 
http://localhost:8080/api/employees/1 >>> is giving employee that id number is 1. 

Using POST Method
http://localhost:8080/api/employees >>> We can add employee, to this endpoint using json file below. The id number will be given automatically from database. 

{
    "firstName": "Mehmet",
    "lastName": "Sargin",
    "email": "mehmetsrgnn@gmail.com"
}

Using PUT Method
http://localhost:8080/api/employees >>> We can update employee to this endpoint using json file below. 

{
    "id":2,
    "firstName": "Mehmet",
    "lastName": "Sargin",
    "email": "mehmetsrgnn@gmail.com"
}

Using DELETE Method
http://localhost:8080/api/employees/5 >>> We can delete employee with that given id number from endpoint. 

