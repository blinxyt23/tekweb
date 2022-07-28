#USERS

GET: /users/

response:
[
{
   "ID"            : "",
    "name"          : "",
    "motto"         : "",
    "ig"        : "",
    "yt"        : "",
    "avatar_url"    : "",
 }
 ]

GET: /users/[id]

reponse:
[
{
    "ID"            : "",
    "name"          : "",
    "motto"         : "",
    "ig"        : "",
    "yt"        : "",
    "avatar_url"    : "",
}
]

POST: /users/
[
{
    "ID"            : "",
    "name"          : "",
    "motto"         : "",
    "ig"        : "",
    "yt"        : "",
    "avatar_url"    : "",
}
]


PUT: /users
data:
[
{
true    // if success
false   // if failure
{
[

response:
[
true    // if success
false   // if failure
[

DELETE: /users/[id]

response:
[
{
true    // if success
false   // if failure
}
]


#ARTICLES
GET: /articles

response:
[
{
        "ID"            : "",
        "title"         : "",
        "content"       : "",
        "thumbnail"     : "",
}
]


GET: /articles/[id]

response:
[
{
    "id"            : "",
    "title"         : "",
    "content"       : "",
    "thumbnail"     : "",
}
]


response:
true    // if success
false   // if failure

POST: /articles/

{
"ID":           "",
"title":        "",
"description":  "",
"thumbnail":    "",
"url":          ""
}

PUT: /articles

data:
[
{
true    // if success
false   // if failure
{
[

response:
true    // if success
false   // if failure

DELETE: /articles/[id]

response:
[
{
true    // if success
false   // if failure
}
]
