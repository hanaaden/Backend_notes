# the principle of REST API

What is REST api 
Representational State Transfer Application is it a rules and Conventions that allow different software applications to communicate and exchange data over internet 

What does the uniform interface principle mean in REST api 

Cuz it establishes standard set of operations that all resources in REST API should support 
For http methods GET , POST , PUT, DELETE

Starting REST API best practice for its UrL structure 

1: use nouns instead of verbs for example use 
/users not /getUsers 

2: use heirarchy let we say we are in the middle of order  instead of just using
 /orders/{orderId} its better if you indicate this order which user it belong to. 
So use /users/{userId}/orders/{orderId} 

3: for collections use plural for example/users

4: consistent convention 
If you decide camelCase in your APi let it all Camel case for the entire API

Versioning 

For better practice REST apis use URL versioning like 
/v1/users 
Use header Versioning 
/vnd.example.v1+json

Versioning Query Parameter 
Easy to implement and test for example use nouns instead /users/?version=1

- use Standard HTTP status codes 
1: 200 OK 
2: 404 not found 
3: 500 internal serval error 
And so on