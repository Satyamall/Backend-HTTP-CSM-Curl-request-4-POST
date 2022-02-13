
### Curl command for Curl-request-4-POST
```js
curl --data "userId=1&id=1&title=delectus aut autem&completed=false" https://jsonplaceholder.typicode.com/todos (make a post request using the /todos endpoint, use the data flag)
```
```js
curl -o todoPost.txt --data "userId=1&id=1&title=delectus aut autem&completed=false" https://jsonplaceholder.typicode.com/todos (to store the todos post request in todoPost.txt)
```



using a similar schema and pass required fields in your request: 
{
    "userId": 1,
    "id": 1,
    "title": "delectus aut autem",
    "completed": false
}

into curl commant below: 
```js
curl --data "userId=1&id=1&title=delectus aut autem&completed=false" https://jsonplaceholder.typicode.com/todos
```


Post response from:
```js
 curl --data "userId=1&id=1&title=delectus aut autem&completed=false" https://jsonplaceholder.typicode.com/todos
 ```
{
  "userId": "1",
  "id": 201,
  "title": "delectus aut autem",
  "completed": "false"
}
