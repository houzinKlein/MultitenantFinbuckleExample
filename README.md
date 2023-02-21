to test the application

- add a new product
- 
POST /products HTTP/1.1
Host: localhost:7001
tenant: Samsung
Content-Type: application/json
Content-Length: 36

{
  "id": 1,
  "name": "Galaxy"
}


-- add another product

POST /products HTTP/1.1
Host: localhost:7001
tenant: Samsung
Content-Type: application/json
Content-Length: 36

{
  "id": 2,
  "name": "Galaxy"
}


-- list all the projects

GET /products HTTP/1.1
Host: localhost:7001
tenant: Samsung
