# server-fakes
For use with: https://jsonplaceholder.typicode.com/

### To facilitate fake server replies 
change the contents of `db.json` with the desired return payload, e.g.:

```
{
  "posts": [
    {
      "id": 1,
      "title": "hello"
    }
  ],
  "profile": {
    "name": "typicode"
  }
}
```

Then call http://my-json-server.typicode.com/sezflynn/server-fakes/posts/1 to get a return of:
```
{
  "id": 1,
  "title": "hello"
}
```

Or call http://my-json-server.typicode.com/sezflynn/server-fakes/profile to get a return of:
```
"name": "typicode"
```
