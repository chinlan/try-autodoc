## GET /todos/:todo_id/items
Returns status code 200.

### Example

#### Request
```
GET /todos/1/items HTTP/1.1
Accept: text/xml,application/xml,application/xhtml+xml,text/html;q=0.9,text/plain;q=0.8,image/png,*/*;q=0.5
Content-Length: 0
Host: www.example.com
```

#### Response
```
HTTP/1.1 200
Cache-Control: max-age=0, private, must-revalidate
Content-Length: 2702
Content-Type: application/json; charset=utf-8
ETag: W/"6e5b5d3324a4394a0ba3fb79506c8ca1"
X-Content-Type-Options: nosniff
X-Frame-Options: SAMEORIGIN
X-Request-Id: 18d0d07f-3a05-473d-b335-91e8586dd72f
X-Runtime: 0.022449
X-XSS-Protection: 1; mode=block

[
  {
    "id": 1,
    "name": "Padme Amidala",
    "done": false,
    "todo_id": 1,
    "created_at": "2017-07-25T05:19:41.703Z",
    "updated_at": "2017-07-25T05:19:41.703Z"
  },
  {
    "id": 2,
    "name": "Watto",
    "done": false,
    "todo_id": 1,
    "created_at": "2017-07-25T05:19:41.708Z",
    "updated_at": "2017-07-25T05:19:41.708Z"
  },
  {
    "id": 3,
    "name": "Jabba the Hutt",
    "done": false,
    "todo_id": 1,
    "created_at": "2017-07-25T05:19:41.711Z",
    "updated_at": "2017-07-25T05:19:41.711Z"
  },
  {
    "id": 4,
    "name": "Luke Skywalker",
    "done": false,
    "todo_id": 1,
    "created_at": "2017-07-25T05:19:41.714Z",
    "updated_at": "2017-07-25T05:19:41.714Z"
  },
  {
    "id": 5,
    "name": "Qui-Gon Jinn",
    "done": false,
    "todo_id": 1,
    "created_at": "2017-07-25T05:19:41.716Z",
    "updated_at": "2017-07-25T05:19:41.716Z"
  },
  {
    "id": 6,
    "name": "Mace Windu",
    "done": false,
    "todo_id": 1,
    "created_at": "2017-07-25T05:19:41.718Z",
    "updated_at": "2017-07-25T05:19:41.718Z"
  },
  {
    "id": 7,
    "name": "Boba Fett",
    "done": false,
    "todo_id": 1,
    "created_at": "2017-07-25T05:19:41.720Z",
    "updated_at": "2017-07-25T05:19:41.720Z"
  },
  {
    "id": 8,
    "name": "Sebulba",
    "done": false,
    "todo_id": 1,
    "created_at": "2017-07-25T05:19:41.723Z",
    "updated_at": "2017-07-25T05:19:41.723Z"
  },
  {
    "id": 9,
    "name": "Poe Dameron",
    "done": false,
    "todo_id": 1,
    "created_at": "2017-07-25T05:19:41.725Z",
    "updated_at": "2017-07-25T05:19:41.725Z"
  },
  {
    "id": 10,
    "name": "Lando Calrissian",
    "done": false,
    "todo_id": 1,
    "created_at": "2017-07-25T05:19:41.729Z",
    "updated_at": "2017-07-25T05:19:41.729Z"
  },
  {
    "id": 11,
    "name": "Ben Solo",
    "done": false,
    "todo_id": 1,
    "created_at": "2017-07-25T05:19:41.733Z",
    "updated_at": "2017-07-25T05:19:41.733Z"
  },
  {
    "id": 12,
    "name": "Ben Solo",
    "done": false,
    "todo_id": 1,
    "created_at": "2017-07-25T05:19:41.735Z",
    "updated_at": "2017-07-25T05:19:41.735Z"
  },
  {
    "id": 13,
    "name": "Padme Amidala",
    "done": false,
    "todo_id": 1,
    "created_at": "2017-07-25T05:19:41.737Z",
    "updated_at": "2017-07-25T05:19:41.737Z"
  },
  {
    "id": 14,
    "name": "Watto",
    "done": false,
    "todo_id": 1,
    "created_at": "2017-07-25T05:19:41.740Z",
    "updated_at": "2017-07-25T05:19:41.740Z"
  },
  {
    "id": 15,
    "name": "Luke Skywalker",
    "done": false,
    "todo_id": 1,
    "created_at": "2017-07-25T05:19:41.742Z",
    "updated_at": "2017-07-25T05:19:41.742Z"
  },
  {
    "id": 16,
    "name": "Bail Organa",
    "done": false,
    "todo_id": 1,
    "created_at": "2017-07-25T05:19:41.746Z",
    "updated_at": "2017-07-25T05:19:41.746Z"
  },
  {
    "id": 17,
    "name": "Jabba the Hutt",
    "done": false,
    "todo_id": 1,
    "created_at": "2017-07-25T05:19:41.750Z",
    "updated_at": "2017-07-25T05:19:41.750Z"
  },
  {
    "id": 18,
    "name": "Watto",
    "done": false,
    "todo_id": 1,
    "created_at": "2017-07-25T05:19:41.752Z",
    "updated_at": "2017-07-25T05:19:41.752Z"
  },
  {
    "id": 19,
    "name": "Rune Haako",
    "done": false,
    "todo_id": 1,
    "created_at": "2017-07-25T05:19:41.755Z",
    "updated_at": "2017-07-25T05:19:41.755Z"
  },
  {
    "id": 20,
    "name": "Count Dooku",
    "done": false,
    "todo_id": 1,
    "created_at": "2017-07-25T05:19:41.757Z",
    "updated_at": "2017-07-25T05:19:41.757Z"
  }
]
```

## GET /todos/:todo_id/items
Returns all todo items.

### Example

#### Request
```
GET /todos/1/items HTTP/1.1
Accept: text/xml,application/xml,application/xhtml+xml,text/html;q=0.9,text/plain;q=0.8,image/png,*/*;q=0.5
Content-Length: 0
Host: www.example.com
```

#### Response
```
HTTP/1.1 200
Cache-Control: max-age=0, private, must-revalidate
Content-Length: 2724
Content-Type: application/json; charset=utf-8
ETag: W/"6861b53fb6325714225b18b560b4309d"
X-Content-Type-Options: nosniff
X-Frame-Options: SAMEORIGIN
X-Request-Id: a6157dd7-2189-457e-89f9-d67b9200a0cd
X-Runtime: 0.012995
X-XSS-Protection: 1; mode=block

[
  {
    "id": 1,
    "name": "Han Solo",
    "done": false,
    "todo_id": 1,
    "created_at": "2017-07-25T05:19:41.795Z",
    "updated_at": "2017-07-25T05:19:41.795Z"
  },
  {
    "id": 2,
    "name": "Jar Jar Binks",
    "done": false,
    "todo_id": 1,
    "created_at": "2017-07-25T05:19:41.799Z",
    "updated_at": "2017-07-25T05:19:41.799Z"
  },
  {
    "id": 3,
    "name": "Darth Caedus",
    "done": false,
    "todo_id": 1,
    "created_at": "2017-07-25T05:19:41.803Z",
    "updated_at": "2017-07-25T05:19:41.803Z"
  },
  {
    "id": 4,
    "name": "Bail Organa",
    "done": false,
    "todo_id": 1,
    "created_at": "2017-07-25T05:19:41.806Z",
    "updated_at": "2017-07-25T05:19:41.806Z"
  },
  {
    "id": 5,
    "name": "Darth Sidious",
    "done": false,
    "todo_id": 1,
    "created_at": "2017-07-25T05:19:41.808Z",
    "updated_at": "2017-07-25T05:19:41.808Z"
  },
  {
    "id": 6,
    "name": "Darth Maul",
    "done": false,
    "todo_id": 1,
    "created_at": "2017-07-25T05:19:41.811Z",
    "updated_at": "2017-07-25T05:19:41.811Z"
  },
  {
    "id": 7,
    "name": "Jango Fett",
    "done": false,
    "todo_id": 1,
    "created_at": "2017-07-25T05:19:41.815Z",
    "updated_at": "2017-07-25T05:19:41.815Z"
  },
  {
    "id": 8,
    "name": "Nute Gunray",
    "done": false,
    "todo_id": 1,
    "created_at": "2017-07-25T05:19:41.818Z",
    "updated_at": "2017-07-25T05:19:41.818Z"
  },
  {
    "id": 9,
    "name": "Ben Solo",
    "done": false,
    "todo_id": 1,
    "created_at": "2017-07-25T05:19:41.820Z",
    "updated_at": "2017-07-25T05:19:41.820Z"
  },
  {
    "id": 10,
    "name": "Jar Jar Binks",
    "done": false,
    "todo_id": 1,
    "created_at": "2017-07-25T05:19:41.823Z",
    "updated_at": "2017-07-25T05:19:41.823Z"
  },
  {
    "id": 11,
    "name": "Ki-Adi-Mundi",
    "done": false,
    "todo_id": 1,
    "created_at": "2017-07-25T05:19:41.825Z",
    "updated_at": "2017-07-25T05:19:41.825Z"
  },
  {
    "id": 12,
    "name": "Ki-Adi-Mundi",
    "done": false,
    "todo_id": 1,
    "created_at": "2017-07-25T05:19:41.829Z",
    "updated_at": "2017-07-25T05:19:41.829Z"
  },
  {
    "id": 13,
    "name": "Sheev Palpatine",
    "done": false,
    "todo_id": 1,
    "created_at": "2017-07-25T05:19:41.832Z",
    "updated_at": "2017-07-25T05:19:41.832Z"
  },
  {
    "id": 14,
    "name": "Poe Dameron",
    "done": false,
    "todo_id": 1,
    "created_at": "2017-07-25T05:19:41.834Z",
    "updated_at": "2017-07-25T05:19:41.834Z"
  },
  {
    "id": 15,
    "name": "Jar Jar Binks",
    "done": false,
    "todo_id": 1,
    "created_at": "2017-07-25T05:19:41.837Z",
    "updated_at": "2017-07-25T05:19:41.837Z"
  },
  {
    "id": 16,
    "name": "Boba Fett",
    "done": false,
    "todo_id": 1,
    "created_at": "2017-07-25T05:19:41.841Z",
    "updated_at": "2017-07-25T05:19:41.841Z"
  },
  {
    "id": 17,
    "name": "Rune Haako",
    "done": false,
    "todo_id": 1,
    "created_at": "2017-07-25T05:19:41.845Z",
    "updated_at": "2017-07-25T05:19:41.845Z"
  },
  {
    "id": 18,
    "name": "Padme Amidala",
    "done": false,
    "todo_id": 1,
    "created_at": "2017-07-25T05:19:41.849Z",
    "updated_at": "2017-07-25T05:19:41.849Z"
  },
  {
    "id": 19,
    "name": "Lando Calrissian",
    "done": false,
    "todo_id": 1,
    "created_at": "2017-07-25T05:19:41.852Z",
    "updated_at": "2017-07-25T05:19:41.852Z"
  },
  {
    "id": 20,
    "name": "Qui-Gon Jinn",
    "done": false,
    "todo_id": 1,
    "created_at": "2017-07-25T05:19:41.856Z",
    "updated_at": "2017-07-25T05:19:41.856Z"
  }
]
```

## GET /todos/:todo_id/items
Returns status code 404.

### Example

#### Request
```
GET /todos/0/items HTTP/1.1
Accept: text/xml,application/xml,application/xhtml+xml,text/html;q=0.9,text/plain;q=0.8,image/png,*/*;q=0.5
Content-Length: 0
Host: www.example.com
```

#### Response
```
HTTP/1.1 404
Cache-Control: no-cache
Content-Length: 44
Content-Type: application/json; charset=utf-8
X-Content-Type-Options: nosniff
X-Frame-Options: SAMEORIGIN
X-Request-Id: 54062e14-81f8-40b7-a38c-12f6c866a944
X-Runtime: 0.003221
X-XSS-Protection: 1; mode=block

{
  "message": "Couldn't find Todo with 'id'=0"
}
```

## GET /todos/:todo_id/items
Returns a not found message.

### Example

#### Request
```
GET /todos/0/items HTTP/1.1
Accept: text/xml,application/xml,application/xhtml+xml,text/html;q=0.9,text/plain;q=0.8,image/png,*/*;q=0.5
Content-Length: 0
Host: www.example.com
```

#### Response
```
HTTP/1.1 404
Cache-Control: no-cache
Content-Length: 44
Content-Type: application/json; charset=utf-8
X-Content-Type-Options: nosniff
X-Frame-Options: SAMEORIGIN
X-Request-Id: 9809dafe-ef75-4f1e-9770-a875606d5f19
X-Runtime: 0.001489
X-XSS-Protection: 1; mode=block

{
  "message": "Couldn't find Todo with 'id'=0"
}
```

## GET /todos/:todo_id/items/:id
Returns status code 200.

### Example

#### Request
```
GET /todos/1/items/1 HTTP/1.1
Accept: text/xml,application/xml,application/xhtml+xml,text/html;q=0.9,text/plain;q=0.8,image/png,*/*;q=0.5
Content-Length: 0
Host: www.example.com
```

#### Response
```
HTTP/1.1 200
Cache-Control: max-age=0, private, must-revalidate
Content-Length: 137
Content-Type: application/json; charset=utf-8
ETag: W/"a4670301ae2be213e25eef9dd10e84f0"
X-Content-Type-Options: nosniff
X-Frame-Options: SAMEORIGIN
X-Request-Id: e16f72e7-acc3-45e6-822a-93ded43489e4
X-Runtime: 0.003583
X-XSS-Protection: 1; mode=block

{
  "id": 1,
  "name": "Wedge Antilles",
  "done": false,
  "todo_id": 1,
  "created_at": "2017-07-25T05:19:42.056Z",
  "updated_at": "2017-07-25T05:19:42.056Z"
}
```

## GET /todos/:todo_id/items/:id
Returns the item.

### Example

#### Request
```
GET /todos/1/items/1 HTTP/1.1
Accept: text/xml,application/xml,application/xhtml+xml,text/html;q=0.9,text/plain;q=0.8,image/png,*/*;q=0.5
Content-Length: 0
Host: www.example.com
```

#### Response
```
HTTP/1.1 200
Cache-Control: max-age=0, private, must-revalidate
Content-Length: 131
Content-Type: application/json; charset=utf-8
ETag: W/"e82a79181f961cac152cf333a25e8854"
X-Content-Type-Options: nosniff
X-Frame-Options: SAMEORIGIN
X-Request-Id: cd19f03e-5122-4882-a8c8-6e841a9a7657
X-Runtime: 0.004008
X-XSS-Protection: 1; mode=block

{
  "id": 1,
  "name": "Ben Solo",
  "done": false,
  "todo_id": 1,
  "created_at": "2017-07-25T05:19:42.129Z",
  "updated_at": "2017-07-25T05:19:42.129Z"
}
```

## GET /todos/:todo_id/items/:id
Returns status code 404.

### Example

#### Request
```
GET /todos/1/items/0 HTTP/1.1
Accept: text/xml,application/xml,application/xhtml+xml,text/html;q=0.9,text/plain;q=0.8,image/png,*/*;q=0.5
Content-Length: 0
Host: www.example.com
```

#### Response
```
HTTP/1.1 404
Cache-Control: no-cache
Content-Length: 96
Content-Type: application/json; charset=utf-8
X-Content-Type-Options: nosniff
X-Frame-Options: SAMEORIGIN
X-Request-Id: a22f820f-5152-4df1-adfd-9bfc40e48ec9
X-Runtime: 0.004856
X-XSS-Protection: 1; mode=block

{
  "message": "Couldn't find Item with [WHERE \"items\".\"todo_id\" = ? AND \"items\".\"id\" = ?]"
}
```

## GET /todos/:todo_id/items/:id
Returns a not found message.

### Example

#### Request
```
GET /todos/1/items/0 HTTP/1.1
Accept: text/xml,application/xml,application/xhtml+xml,text/html;q=0.9,text/plain;q=0.8,image/png,*/*;q=0.5
Content-Length: 0
Host: www.example.com
```

#### Response
```
HTTP/1.1 404
Cache-Control: no-cache
Content-Length: 96
Content-Type: application/json; charset=utf-8
X-Content-Type-Options: nosniff
X-Frame-Options: SAMEORIGIN
X-Request-Id: 8f997607-f399-433b-8dc2-a7b411952d65
X-Runtime: 0.003046
X-XSS-Protection: 1; mode=block

{
  "message": "Couldn't find Item with [WHERE \"items\".\"todo_id\" = ? AND \"items\".\"id\" = ?]"
}
```

## POST /todos/:todo_id/items
Returns status code 201.

### Example

#### Request
```
POST /todos/1/items HTTP/1.1
Accept: text/xml,application/xml,application/xhtml+xml,text/html;q=0.9,text/plain;q=0.8,image/png,*/*;q=0.5
Content-Length: 28
Content-Type: application/x-www-form-urlencoded
Host: www.example.com

name=Visit+Narnia&done=false
```

#### Response
```
HTTP/1.1 201
Cache-Control: max-age=0, private, must-revalidate
Content-Length: 136
Content-Type: application/json; charset=utf-8
ETag: W/"b536b24b4eae1ca79df0ad78ab82f233"
X-Content-Type-Options: nosniff
X-Frame-Options: SAMEORIGIN
X-Request-Id: 85c45897-1892-4f9c-9013-56ef6eaf59d7
X-Runtime: 0.008088
X-XSS-Protection: 1; mode=block

{
  "id": 1,
  "title": "accusantium",
  "created_by": "4798228037",
  "created_at": "2017-07-25T05:19:42.328Z",
  "updated_at": "2017-07-25T05:19:42.328Z"
}
```

## POST /todos/:todo_id/items
Returns status code 422.

### Example

#### Request
```
POST /todos/1/items HTTP/1.1
Accept: text/xml,application/xml,application/xhtml+xml,text/html;q=0.9,text/plain;q=0.8,image/png,*/*;q=0.5
Content-Length: 0
Content-Type: application/x-www-form-urlencoded
Host: www.example.com
```

#### Response
```
HTTP/1.1 422
Cache-Control: no-cache
Content-Length: 52
Content-Type: application/json; charset=utf-8
X-Content-Type-Options: nosniff
X-Frame-Options: SAMEORIGIN
X-Request-Id: 1b48620f-e52b-4b61-8ff9-39a3f44a087e
X-Runtime: 0.003663
X-XSS-Protection: 1; mode=block

{
  "message": "Validation failed: Name can't be blank"
}
```

## POST /todos/:todo_id/items
Returns a failure message.

### Example

#### Request
```
POST /todos/1/items HTTP/1.1
Accept: text/xml,application/xml,application/xhtml+xml,text/html;q=0.9,text/plain;q=0.8,image/png,*/*;q=0.5
Content-Length: 0
Content-Type: application/x-www-form-urlencoded
Host: www.example.com
```

#### Response
```
HTTP/1.1 422
Cache-Control: no-cache
Content-Length: 52
Content-Type: application/json; charset=utf-8
X-Content-Type-Options: nosniff
X-Frame-Options: SAMEORIGIN
X-Request-Id: a4348430-8445-48ae-a037-14344b6a8160
X-Runtime: 0.003824
X-XSS-Protection: 1; mode=block

{
  "message": "Validation failed: Name can't be blank"
}
```

## PUT /todos/:todo_id/items/:id
Returns status code 204.

### Example

#### Request
```
PUT /todos/1/items/1 HTTP/1.1
Accept: text/xml,application/xml,application/xhtml+xml,text/html;q=0.9,text/plain;q=0.8,image/png,*/*;q=0.5
Content-Length: 11
Content-Type: application/x-www-form-urlencoded
Host: www.example.com

name=Mozart
```

#### Response
```
HTTP/1.1 204
Cache-Control: no-cache
X-Content-Type-Options: nosniff
X-Frame-Options: SAMEORIGIN
X-Request-Id: 31e724ef-2729-467a-be5d-1d6f42cb5b03
X-Runtime: 0.005386
X-XSS-Protection: 1; mode=block
```

## PUT /todos/:todo_id/items/:id
Updates the item.

### Example

#### Request
```
PUT /todos/1/items/1 HTTP/1.1
Accept: text/xml,application/xml,application/xhtml+xml,text/html;q=0.9,text/plain;q=0.8,image/png,*/*;q=0.5
Content-Length: 11
Content-Type: application/x-www-form-urlencoded
Host: www.example.com

name=Mozart
```

#### Response
```
HTTP/1.1 204
Cache-Control: no-cache
X-Content-Type-Options: nosniff
X-Frame-Options: SAMEORIGIN
X-Request-Id: 68f80925-915c-4b37-a475-23bf356f1dce
X-Runtime: 0.004051
X-XSS-Protection: 1; mode=block
```

## PUT /todos/:todo_id/items/:id
Returns status code 404.

### Example

#### Request
```
PUT /todos/1/items/0 HTTP/1.1
Accept: text/xml,application/xml,application/xhtml+xml,text/html;q=0.9,text/plain;q=0.8,image/png,*/*;q=0.5
Content-Length: 11
Content-Type: application/x-www-form-urlencoded
Host: www.example.com

name=Mozart
```

#### Response
```
HTTP/1.1 404
Cache-Control: no-cache
Content-Length: 96
Content-Type: application/json; charset=utf-8
X-Content-Type-Options: nosniff
X-Frame-Options: SAMEORIGIN
X-Request-Id: d3cf54ce-d855-4d92-9891-6087b5d6873f
X-Runtime: 0.002725
X-XSS-Protection: 1; mode=block

{
  "message": "Couldn't find Item with [WHERE \"items\".\"todo_id\" = ? AND \"items\".\"id\" = ?]"
}
```

## PUT /todos/:todo_id/items/:id
Returns a not found message.

### Example

#### Request
```
PUT /todos/1/items/0 HTTP/1.1
Accept: text/xml,application/xml,application/xhtml+xml,text/html;q=0.9,text/plain;q=0.8,image/png,*/*;q=0.5
Content-Length: 11
Content-Type: application/x-www-form-urlencoded
Host: www.example.com

name=Mozart
```

#### Response
```
HTTP/1.1 404
Cache-Control: no-cache
Content-Length: 96
Content-Type: application/json; charset=utf-8
X-Content-Type-Options: nosniff
X-Frame-Options: SAMEORIGIN
X-Request-Id: ca46f747-8eb2-427c-ba21-9529182d477e
X-Runtime: 0.002871
X-XSS-Protection: 1; mode=block

{
  "message": "Couldn't find Item with [WHERE \"items\".\"todo_id\" = ? AND \"items\".\"id\" = ?]"
}
```

## DELETE /todos/:id
Returns status code 204.

### Example

#### Request
```
DELETE /todos/1/items/1 HTTP/1.1
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
X-Request-Id: 90ca09a0-4b4f-4fce-95d9-26b2c5c177c9
X-Runtime: 0.003357
X-XSS-Protection: 1; mode=block
```
