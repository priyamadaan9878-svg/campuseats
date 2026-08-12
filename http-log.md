# HTTP Request/Response Log

## Request 1 — Get Post 1

### Request

```bash
curl -i https://jsonplaceholder.typicode.com/posts/1
```

### Response



```text

HTTP/2 200 
date: Wed, 12 Aug 2026 15:15:35 GMT
content-type: application/json; charset=utf-8
content-length: 292
access-control-allow-credentials: true
cache-control: max-age=43200
etag: W/"124-yiKdLzqO5gfBrJFrcdJ8Yq0LGnU"
expires: -1
nel: {"report_to":"heroku-nel","response_headers":["Via"],"max_age":3600,"success_fraction":0.01,"failure_fraction":0.1}
pragma: no-cache
report-to: {"group":"heroku-nel","endpoints":[{"url":"https://nel.heroku.com/reports?s=UyhbZ%2F0MO1mJoZS7M4Hj8SWBXp3NkwnJgHEYoqocyDE%3D\u0026sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d\u0026ts=1785191026"}],"max_age":3600}
reporting-endpoints: heroku-nel="https://nel.heroku.com/reports?s=UyhbZ%2F0MO1mJoZS7M4Hj8SWBXp3NkwnJgHEYoqocyDE%3D&sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d&ts=1785191026"
server: cloudflare
vary: Origin, Accept-Encoding
via: 2.0 heroku-router
x-content-type-options: nosniff
x-powered-by: Express
x-ratelimit-limit: 1000
x-ratelimit-remaining: 999
x-ratelimit-reset: 1785191063
age: 25790
accept-ranges: bytes
cf-cache-status: HIT
cf-ray: a2a06fb35c1bf5d9-AMS
alt-svc: h3=":443"; ma=86400

{
  "userId": 1,
  "id": 1,
  "title": "sunt aut facere repellat provident occaecati excepturi optio reprehenderit",
  "body": "quia et suscipit\nsuscipit recusandae consequuntur expedita et cum\nreprehenderit molestiae ut ut quas totam\nnostrum rerum est autem sunt rem eveniet architecto"
}
```

### Annotation

- `200 OK` — The request was successful and the post was found.
- `Content-Type: application/json; charset=utf-8` — The response contains JSON data encoded in UTF-8.


## Request 2 — Get Comment 1

### Request

```bash
curl -i https://jsonplaceholder.typicode.com/comments/1
```

### Response

```text
                                                                                            
HTTP/2 200 
date: Wed, 12 Aug 2026 15:16:11 GMT
content-type: application/json; charset=utf-8
content-length: 268
access-control-allow-credentials: true
cache-control: max-age=43200
etag: W/"10c-KJ4I9RM/+33TKdV8CFsIvqsDSP0"
expires: -1
nel: {"report_to":"heroku-nel","response_headers":["Via"],"max_age":3600,"success_fraction":0.01,"failure_fraction":0.1}
pragma: no-cache
report-to: {"group":"heroku-nel","endpoints":[{"url":"https://nel.heroku.com/reports?s=BqnMU0lnJxjIRJpYuklYO4VyVWmDriUllFwfI5OZAuY%3D\u0026sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d\u0026ts=1786521917"}],"max_age":3600}
reporting-endpoints: heroku-nel="https://nel.heroku.com/reports?s=BqnMU0lnJxjIRJpYuklYO4VyVWmDriUllFwfI5OZAuY%3D&sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d&ts=1786521917"
server: cloudflare
vary: Origin, Accept-Encoding
via: 2.0 heroku-router
x-content-type-options: nosniff
x-powered-by: Express
x-ratelimit-limit: 1000
x-ratelimit-remaining: 931
x-ratelimit-reset: 1786521955
age: 25854
accept-ranges: bytes
cf-cache-status: HIT
cf-ray: a2a07095f9e5fd2c-SIN
alt-svc: h3=":443"; ma=86400

{
  "postId": 1,
  "id": 1,
  "name": "id labore ex et quam laborum",
  "email": "Eliseo@gardner.biz",
  "body": "laudantium enim quasi est quidem magnam voluptate ipsam eos\ntempora quo necessitatibus\ndolor quam autem quasi\nreiciendis et nam sapiente accusantium"
}                                                                                                                  
```

### Annotation

- `200 OK` — The request was successful and the comment was found.
- `Content-Type: application/json; charset=utf-8` — The response contains JSON data encoded in UTF-8.



## Request 3 — Get User 1

### Request

```bash
curl -i https://jsonplaceholder.typicode.com/users/1
```

### Response

```text


HTTP/2 200 
date: Wed, 12 Aug 2026 15:16:43 GMT
content-type: application/json; charset=utf-8
content-length: 509
access-control-allow-credentials: true
cache-control: max-age=43200
etag: W/"1fd-+2Y3G3w049iSZtw5t1mzSnunngE"
expires: -1
nel: {"report_to":"heroku-nel","response_headers":["Via"],"max_age":3600,"success_fraction":0.01,"failure_fraction":0.1}
pragma: no-cache
report-to: {"group":"heroku-nel","endpoints":[{"url":"https://nel.heroku.com/reports?s=m23T6Tj%2BQUZnIwphHAim1ChY9yjwiqMeEy5yHiMrfN0%3D\u0026sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d\u0026ts=1785634999"}],"max_age":3600}
reporting-endpoints: heroku-nel="https://nel.heroku.com/reports?s=m23T6Tj%2BQUZnIwphHAim1ChY9yjwiqMeEy5yHiMrfN0%3D&sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d&ts=1785634999"
server: cloudflare
vary: Origin, Accept-Encoding
via: 2.0 heroku-router
x-content-type-options: nosniff
x-powered-by: Express
x-ratelimit-limit: 1000
x-ratelimit-remaining: 999
x-ratelimit-reset: 1785635057
age: 12398
accept-ranges: bytes
cf-cache-status: HIT
cf-ray: a2a0715dee973c6d-AMS
alt-svc: h3=":443"; ma=86400

{
  "id": 1,
  "name": "Leanne Graham",
  "username": "Bret",
  "email": "Sincere@april.biz",
  "address": {
    "street": "Kulas Light",
    "suite": "Apt. 556",
    "city": "Gwenborough",
    "zipcode": "92998-3874",
    "geo": {
      "lat": "-37.3159",
      "lng": "81.1496"
    }
  },
  "phone": "1-770-736-8031 x56442",
  "website": "hildegard.org",
  "company": {
    "name": "Romaguera-Crona",
    "catchPhrase": "Multi-layered client-server neural-net",
    "bs": "harness real-time e-markets"
  }
}
```

### Annotation

- `200 OK` — The request was successful and the user was found.
- `Content-Type: application/json; charset=utf-8` — The response contains JSON data encoded in UTF-8.


## Request 4 — Get Todo 1

### Request

```bash
curl -i https://jsonplaceholder.typicode.com/todos/1
```

### Response

```text

HTTP/2 200 
date: Wed, 12 Aug 2026 15:17:19 GMT
content-type: application/json; charset=utf-8
content-length: 83
access-control-allow-credentials: true
cache-control: max-age=43200
etag: W/"53-hfEnumeNh6YirfjyjaujcOPPT+s"
expires: -1
nel: {"report_to":"heroku-nel","response_headers":["Via"],"max_age":3600,"success_fraction":0.01,"failure_fraction":0.1}
pragma: no-cache
report-to: {"group":"heroku-nel","endpoints":[{"url":"https://nel.heroku.com/reports?s=o3LnB4y9klD2bC%2B9j%2F4juYbUmCEOESrp8RutkrsBB%2BY%3D\u0026sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d\u0026ts=1776956825"}],"max_age":3600}
reporting-endpoints: heroku-nel="https://nel.heroku.com/reports?s=o3LnB4y9klD2bC%2B9j%2F4juYbUmCEOESrp8RutkrsBB%2BY%3D&sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d&ts=1776956825"
server: cloudflare
vary: Origin, Accept-Encoding
via: 2.0 heroku-router
x-content-type-options: nosniff
x-powered-by: Express
x-ratelimit-limit: 1000
x-ratelimit-remaining: 999
x-ratelimit-reset: 1776956878
age: 6
accept-ranges: bytes
cf-cache-status: HIT
cf-ray: a2a0723a08c0ff93-SIN
alt-svc: h3=":443"; ma=86400

{
  "userId": 1,
  "id": 1,
  "title": "delectus aut autem",
  "completed": false
}
```

### Annotation

- `200 OK` — The request was successful and the todo item was found.
- `Content-Type: application/json; charset=utf-8` — The response contains JSON data encoded in UTF-8.


## Request 5 — Non-existent Post

### Request

```bash
curl -i https://jsonplaceholder.typicode.com/posts/999999
```

### Response

```text

HTTP/2 404 
date: Wed, 12 Aug 2026 15:17:44 GMT
content-type: application/json; charset=utf-8
content-length: 2
access-control-allow-credentials: true
cache-control: max-age=43200
etag: W/"2-vyGp6PvFo4RvsFtPoIWeCReyIC8"
expires: -1
nel: {"report_to":"heroku-nel","response_headers":["Via"],"max_age":3600,"success_fraction":0.01,"failure_fraction":0.1}
pragma: no-cache
report-to: {"group":"heroku-nel","endpoints":[{"url":"https://nel.heroku.com/reports?s=udRXXsGVfkIxcJVRC0B7fxv31TMqUHKIc5IUyhQAPJg%3D\u0026sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d\u0026ts=1786521855"}],"max_age":3600}
reporting-endpoints: heroku-nel="https://nel.heroku.com/reports?s=udRXXsGVfkIxcJVRC0B7fxv31TMqUHKIc5IUyhQAPJg%3D&sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d&ts=1786521855"
server: cloudflare
vary: Origin, Accept-Encoding
via: 2.0 heroku-router
x-content-type-options: nosniff
x-powered-by: Express
x-ratelimit-limit: 1000
x-ratelimit-remaining: 999
x-ratelimit-reset: 1786521895
age: 26009
cf-cache-status: HIT
cf-ray: a2a072d9a8589700-AMS
alt-svc: h3=":443"; ma=86400

{}
```

### Annotation

- `404 Not Found` — The requested post does not exist.
- `Content-Type: application/json; charset=utf-8` — The response is returned in JSON format using UTF-8 encoding.



