# student-management-system

## Mohammad Naim Almani
### GET all students
http://localhost:8080/student-management-system/api/v1/student	              
### Get student by his last name 
http://localhost:8080/student-management-system/api/v1/student/lastname
### GET student by id
http://localhost:8080/student-management-system/api/v1/student/{id}
### POST: create student
http://localhost:8080/student-management-system/api/v1/student
### PUT  update student
http://localhost:8080/student-management-system/api/v1/student	           
### DELETE student by id
http://localhost:8080/student-management-system/api/v1/student/{id}
### PATCH: update student email
http://localhost:8080/student-management-system/api/v1/student/{id}


#### create json Format :
{
"firstName": " your first name",
"lastName": "your last name",
"email": "you@exemple.com",
"phoneNumber": "your phone number"
}

#### update json Format :
{
"firstName": " your first name",
"lastName": "your last name",
"email": "you@exemple.com",
"phoneNumber": "your phone number"
}
