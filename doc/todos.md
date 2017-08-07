## GET /todos
Returns todos.

### Example

#### Request
```
GET /todos HTTP/1.1
Accept: text/xml,application/xml,application/xhtml+xml,text/html;q=0.9,text/plain;q=0.8,image/png,*/*;q=0.5
Content-Length: 0
Host: www.example.com
```

#### Response
```
HTTP/1.1 200
Cache-Control: max-age=0, private, must-revalidate
Content-Length: 1327
Content-Type: application/json; charset=utf-8
ETag: W/"a9043ef4fad0eedde8a73dec4625c5af"
X-Content-Type-Options: nosniff
X-Frame-Options: SAMEORIGIN
X-Request-Id: a8e799a9-7060-4c5c-9a74-36c05ef751a8
X-Runtime: 0.003695
X-XSS-Protection: 1; mode=block

[
  {
    "id": 1,
    "title": "ea",
    "created_by": "2447904730",
    "created_at": "2017-07-25T05:19:42.796Z",
    "updated_at": "2017-07-25T05:19:42.796Z"
  },
  {
    "id": 2,
    "title": "nisi",
    "created_by": "3137540015",
    "created_at": "2017-07-25T05:19:42.797Z",
    "updated_at": "2017-07-25T05:19:42.797Z"
  },
  {
    "id": 3,
    "title": "maiores",
    "created_by": "8297386667",
    "created_at": "2017-07-25T05:19:42.798Z",
    "updated_at": "2017-07-25T05:19:42.798Z"
  },
  {
    "id": 4,
    "title": "temporibus",
    "created_by": "4457892502",
    "created_at": "2017-07-25T05:19:42.799Z",
    "updated_at": "2017-07-25T05:19:42.799Z"
  },
  {
    "id": 5,
    "title": "voluptatem",
    "created_by": "9114138474",
    "created_at": "2017-07-25T05:19:42.800Z",
    "updated_at": "2017-07-25T05:19:42.800Z"
  },
  {
    "id": 6,
    "title": "nihil",
    "created_by": "1989511265",
    "created_at": "2017-07-25T05:19:42.802Z",
    "updated_at": "2017-07-25T05:19:42.802Z"
  },
  {
    "id": 7,
    "title": "optio",
    "created_by": "5154126610",
    "created_at": "2017-07-25T05:19:42.803Z",
    "updated_at": "2017-07-25T05:19:42.803Z"
  },
  {
    "id": 8,
    "title": "maiores",
    "created_by": "3692057839",
    "created_at": "2017-07-25T05:19:42.804Z",
    "updated_at": "2017-07-25T05:19:42.804Z"
  },
  {
    "id": 9,
    "title": "consequuntur",
    "created_by": "8754782782",
    "created_at": "2017-07-25T05:19:42.806Z",
    "updated_at": "2017-07-25T05:19:42.806Z"
  },
  {
    "id": 10,
    "title": "est",
    "created_by": "3449102627",
    "created_at": "2017-07-25T05:19:42.807Z",
    "updated_at": "2017-07-25T05:19:42.807Z"
  }
]
```

## GET /todos
Returns status code 200.

### Example

#### Request
```
GET /todos HTTP/1.1
Accept: text/xml,application/xml,application/xhtml+xml,text/html;q=0.9,text/plain;q=0.8,image/png,*/*;q=0.5
Content-Length: 0
Host: www.example.com
```

#### Response
```
HTTP/1.1 200
Cache-Control: max-age=0, private, must-revalidate
Content-Length: 1311
Content-Type: application/json; charset=utf-8
ETag: W/"6668988b2c89f2aa5c9d4fd4e402a8ce"
X-Content-Type-Options: nosniff
X-Frame-Options: SAMEORIGIN
X-Request-Id: 31784d7c-69cc-467a-9e2c-c95f143c7f4c
X-Runtime: 0.002800
X-XSS-Protection: 1; mode=block

[
  {
    "id": 1,
    "title": "architecto",
    "created_by": "6248635468",
    "created_at": "2017-07-25T05:19:42.817Z",
    "updated_at": "2017-07-25T05:19:42.817Z"
  },
  {
    "id": 2,
    "title": "nisi",
    "created_by": "5438615762",
    "created_at": "2017-07-25T05:19:42.819Z",
    "updated_at": "2017-07-25T05:19:42.819Z"
  },
  {
    "id": 3,
    "title": "vel",
    "created_by": "9295361994",
    "created_at": "2017-07-25T05:19:42.820Z",
    "updated_at": "2017-07-25T05:19:42.820Z"
  },
  {
    "id": 4,
    "title": "hic",
    "created_by": "9309479136",
    "created_at": "2017-07-25T05:19:42.821Z",
    "updated_at": "2017-07-25T05:19:42.821Z"
  },
  {
    "id": 5,
    "title": "rerum",
    "created_by": "6275521108",
    "created_at": "2017-07-25T05:19:42.822Z",
    "updated_at": "2017-07-25T05:19:42.822Z"
  },
  {
    "id": 6,
    "title": "qui",
    "created_by": "9908297151",
    "created_at": "2017-07-25T05:19:42.824Z",
    "updated_at": "2017-07-25T05:19:42.824Z"
  },
  {
    "id": 7,
    "title": "odit",
    "created_by": "8648518688",
    "created_at": "2017-07-25T05:19:42.825Z",
    "updated_at": "2017-07-25T05:19:42.825Z"
  },
  {
    "id": 8,
    "title": "hic",
    "created_by": "9989879362",
    "created_at": "2017-07-25T05:19:42.826Z",
    "updated_at": "2017-07-25T05:19:42.826Z"
  },
  {
    "id": 9,
    "title": "animi",
    "created_by": "7871078610",
    "created_at": "2017-07-25T05:19:42.827Z",
    "updated_at": "2017-07-25T05:19:42.827Z"
  },
  {
    "id": 10,
    "title": "molestias",
    "created_by": "7240475145",
    "created_at": "2017-07-25T05:19:42.828Z",
    "updated_at": "2017-07-25T05:19:42.828Z"
  }
]
```

## GET /todos/:id
Returns the todo.

### Example

#### Request
```
GET /todos/1 HTTP/1.1
Accept: text/xml,application/xml,application/xhtml+xml,text/html;q=0.9,text/plain;q=0.8,image/png,*/*;q=0.5
Content-Length: 0
Host: www.example.com
```

#### Response
```
HTTP/1.1 200
Cache-Control: max-age=0, private, must-revalidate
Content-Length: 127
Content-Type: application/json; charset=utf-8
ETag: W/"f987d267d831887eeaf5c01ecd134629"
X-Content-Type-Options: nosniff
X-Frame-Options: SAMEORIGIN
X-Request-Id: 7b2c42fc-68b4-4ec1-b2a5-1678c6df19dd
X-Runtime: 0.001904
X-XSS-Protection: 1; mode=block

{
  "id": 1,
  "title": "in",
  "created_by": "9181847657",
  "created_at": "2017-07-25T05:19:42.837Z",
  "updated_at": "2017-07-25T05:19:42.837Z"
}
```

## GET /todos/:id
Returns status code 200.

### Example

#### Request
```
GET /todos/1 HTTP/1.1
Accept: text/xml,application/xml,application/xhtml+xml,text/html;q=0.9,text/plain;q=0.8,image/png,*/*;q=0.5
Content-Length: 0
Host: www.example.com
```

#### Response
```
HTTP/1.1 200
Cache-Control: max-age=0, private, must-revalidate
Content-Length: 129
Content-Type: application/json; charset=utf-8
ETag: W/"2295bc93f7036cc85bc19861bffa8e84"
X-Content-Type-Options: nosniff
X-Frame-Options: SAMEORIGIN
X-Request-Id: 07db7dc0-2a45-42dd-b8a4-018cd13edd25
X-Runtime: 0.002519
X-XSS-Protection: 1; mode=block

{
  "id": 1,
  "title": "quis",
  "created_by": "2215195735",
  "created_at": "2017-07-25T05:19:42.858Z",
  "updated_at": "2017-07-25T05:19:42.858Z"
}
```

## GET /todos/:id
Returns status code 404.

### Example

#### Request
```
GET /todos/100 HTTP/1.1
Accept: text/xml,application/xml,application/xhtml+xml,text/html;q=0.9,text/plain;q=0.8,image/png,*/*;q=0.5
Content-Length: 0
Host: www.example.com
```

#### Response
```
HTTP/1.1 404
Cache-Control: no-cache
Content-Length: 46
Content-Type: application/json; charset=utf-8
X-Content-Type-Options: nosniff
X-Frame-Options: SAMEORIGIN
X-Request-Id: 7e751f0d-a24e-45fd-aec8-3659cfa4869e
X-Runtime: 0.001658
X-XSS-Protection: 1; mode=block

{
  "message": "Couldn't find Todo with 'id'=100"
}
```

## GET /todos/:id
Returns a not found message.

### Example

#### Request
```
GET /todos/100 HTTP/1.1
Accept: text/xml,application/xml,application/xhtml+xml,text/html;q=0.9,text/plain;q=0.8,image/png,*/*;q=0.5
Content-Length: 0
Host: www.example.com
```

#### Response
```
HTTP/1.1 404
Cache-Control: no-cache
Content-Length: 46
Content-Type: application/json; charset=utf-8
X-Content-Type-Options: nosniff
X-Frame-Options: SAMEORIGIN
X-Request-Id: e90b481e-f8bc-4118-b74f-dd6e538709aa
X-Runtime: 0.001456
X-XSS-Protection: 1; mode=block

{
  "message": "Couldn't find Todo with 'id'=100"
}
```

## POST /todos
Creates a todo.

### Example

#### Request
```
POST /todos HTTP/1.1
Accept: text/xml,application/xml,application/xhtml+xml,text/html;q=0.9,text/plain;q=0.8,image/png,*/*;q=0.5
Content-Length: 28
Content-Type: application/x-www-form-urlencoded
Host: www.example.com

title=Learn+Elm&created_by=1
```

#### Response
```
HTTP/1.1 201
Cache-Control: max-age=0, private, must-revalidate
Content-Length: 126
Content-Type: application/json; charset=utf-8
ETag: W/"642040498f17204cac421c8dc0892d2c"
X-Content-Type-Options: nosniff
X-Frame-Options: SAMEORIGIN
X-Request-Id: 4c27cd2c-0cc8-4cf4-bfba-4fe42f739491
X-Runtime: 0.002690
X-XSS-Protection: 1; mode=block

{
  "id": 11,
  "title": "Learn Elm",
  "created_by": "1",
  "created_at": "2017-07-25T05:19:42.933Z",
  "updated_at": "2017-07-25T05:19:42.933Z"
}
```

## POST /todos
Returns status code 201.

### Example

#### Request
```
POST /todos HTTP/1.1
Accept: text/xml,application/xml,application/xhtml+xml,text/html;q=0.9,text/plain;q=0.8,image/png,*/*;q=0.5
Content-Length: 28
Content-Type: application/x-www-form-urlencoded
Host: www.example.com

title=Learn+Elm&created_by=1
```

#### Response
```
HTTP/1.1 201
Cache-Control: max-age=0, private, must-revalidate
Content-Length: 126
Content-Type: application/json; charset=utf-8
ETag: W/"59364126b0f6e6019512822426293570"
X-Content-Type-Options: nosniff
X-Frame-Options: SAMEORIGIN
X-Request-Id: 2836fdcc-083c-41cd-b1d9-6dee098fe6e2
X-Runtime: 0.003941
X-XSS-Protection: 1; mode=block

{
  "id": 11,
  "title": "Learn Elm",
  "created_by": "1",
  "created_at": "2017-07-25T05:19:42.956Z",
  "updated_at": "2017-07-25T05:19:42.956Z"
}
```

## POST /todos
Returns status code 422.

### Example

#### Request
```
POST /todos HTTP/1.1
Accept: text/xml,application/xml,application/xhtml+xml,text/html;q=0.9,text/plain;q=0.8,image/png,*/*;q=0.5
Content-Length: 12
Content-Type: application/x-www-form-urlencoded
Host: www.example.com

title=Foobar
```

#### Response
```
HTTP/1.1 422
Cache-Control: no-cache
Content-Length: 58
Content-Type: application/json; charset=utf-8
X-Content-Type-Options: nosniff
X-Frame-Options: SAMEORIGIN
X-Request-Id: bc00f55e-a775-428b-a437-331b220e0772
X-Runtime: 0.002440
X-XSS-Protection: 1; mode=block

{
  "message": "Validation failed: Created by can't be blank"
}
```

## POST /todos
Returns a validation failure message.

### Example

#### Request
```
POST /todos HTTP/1.1
Accept: text/xml,application/xml,application/xhtml+xml,text/html;q=0.9,text/plain;q=0.8,image/png,*/*;q=0.5
Content-Length: 12
Content-Type: application/x-www-form-urlencoded
Host: www.example.com

title=Foobar
```

#### Response
```
HTTP/1.1 422
Cache-Control: no-cache
Content-Length: 58
Content-Type: application/json; charset=utf-8
X-Content-Type-Options: nosniff
X-Frame-Options: SAMEORIGIN
X-Request-Id: f3b3a3ef-8e6f-4e42-a74c-233254565ee6
X-Runtime: 0.002103
X-XSS-Protection: 1; mode=block

{
  "message": "Validation failed: Created by can't be blank"
}
```

## PUT /todos/:id
Updates the record.

### Example

#### Request
```
PUT /todos/1 HTTP/1.1
Accept: text/xml,application/xml,application/xhtml+xml,text/html;q=0.9,text/plain;q=0.8,image/png,*/*;q=0.5
Content-Length: 14
Content-Type: application/x-www-form-urlencoded
Host: www.example.com

title=Shopping
```

#### Response
```
HTTP/1.1 204
Cache-Control: no-cache
X-Content-Type-Options: nosniff
X-Frame-Options: SAMEORIGIN
X-Request-Id: 25994c18-d436-40ae-97ea-afce4d5761c8
X-Runtime: 0.003333
X-XSS-Protection: 1; mode=block
```

## PUT /todos/:id
Returns status code 204.

### Example

#### Request
```
PUT /todos/1 HTTP/1.1
Accept: text/xml,application/xml,application/xhtml+xml,text/html;q=0.9,text/plain;q=0.8,image/png,*/*;q=0.5
Content-Length: 14
Content-Type: application/x-www-form-urlencoded
Host: www.example.com

title=Shopping
```

#### Response
```
HTTP/1.1 204
Cache-Control: no-cache
X-Content-Type-Options: nosniff
X-Frame-Options: SAMEORIGIN
X-Request-Id: dfe73bed-ce0f-4973-b895-8d39dfc6c2d5
X-Runtime: 0.003148
X-XSS-Protection: 1; mode=block
```

## DELETE /todos/:id
Returns status code 204.

### Example

#### Request
```
DELETE /todos/1 HTTP/1.1
Accept: text/xml,application/xml,application/xhtml+xml,text/html;q=0.9,text/plain;q=0.8,image/png,*/*;q=0.5
Content-Length: 0
Content-Type: application/x-www-form-urlencoded
Host: www.example.com
```

#### Response
```
HTTP/1.1 204
Cache-Control: no-cache
X-Content-Type-Options: nosniff
X-Frame-Options: SAMEORIGIN
X-Request-Id: a0a62170-5c33-4601-919a-473e342de143
X-Runtime: 0.003267
X-XSS-Protection: 1; mode=block
```
