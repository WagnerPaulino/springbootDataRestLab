# springbootDataRestLab

## Como usar

```bash
curl http://localhost:8080/people
```
 
```bash
curl -i -X POST -H "Content-Type:application/json" -d "{  \"firstName\" : \"Frodo\",  \"lastName\" : \"Baggins\" }" http://localhost:8080/people
```

```bash
curl -X PUT -H "Content-Type:application/json" -d "{ \"firstName\": \"Bilbo\", \"lastName\": \"Baggins\" }" http://localhost:8080/people/1
``` 

```bash
curl -X DELETE http://localhost:8080/people/1
```