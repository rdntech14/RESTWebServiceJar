Rest Service Jar to run locally
=====

This is a rest service jar that can be executed locally to test GET, PUT or POST etc request. 

Download and Run following command

```
java -jar rest.jar
```

**GET/PUT/POST examples**

**GET**

url : http://localhost:8080/student/list


**POST**

url : http://localhost:8080/student 

body : 
```
{
	"id": 1111,
	"firstName": "Vernon",
	"lastName": "Harper",
	"email": "1111@gmail.com",
	"programme": "Financial Analysis",
	"courses": [
		"Accounting",
		"Statistics"
	]
}
```

**PUT**

url : http://localhost:8080/student/1 

body : 
```
{
	"id": 1,
	"firstName": "Vernon",
	"lastName": "Harper",
	"email": "1111aaaa@gmail.com",
	"programme": "Financial Analysis",
	"courses": [
		"computer",
		"Statistics"
	]
}
```