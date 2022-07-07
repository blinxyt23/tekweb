GET: /users/[ID]

response:
[
{
    "ID"        : "",
    "Nama"      : "",
    "Avatar_URL : "",
    "Motto"     : "",
    "Github_URL : "",
    "IG_URL     : "",
 }
 ]

GET: /users/[id]

reponse:
[
{
    "id"            : "",
    "name"          : "",
    "motto"         : "",
    "ig_url"        : "",
    "fb_url"        : "",
    "girhub_url"    : "",
    "avatar_url"    : "",
}
]

GET: /portfolios

response:
[
    {
        "id"            : "",
        "author_id"     : "",
        "author_name"   : "",
        "title"         : "",
        "description    : "",
        "thumbnail_url" : "",
        "technologies"  : "",
    }
 ]
GET: /portfolios/author/author_id

response:
[
    {
        "id"            : "",
        "author_id"     : "",
        "author_name"   : "",
        "title"         : "",
        "description    : "",
        "thumbnail_url" : "",
        "technologies"  : "",
    },
]

GET: /articles

response:
[
{
        "id"            : "",
        "author_id"     : "",
        "author_name"   : "",
        "title"         : "",
        "content"       : "",
        "thumbnail_url" : "",
        "author_id"     : "",
        "created_date"  : ""
}
]


GET: /articles/[id]

response:
[
{
    "id"            : "",
    "author_id"     : "",
    "author_name"   : "",
    "title"         : "",
    "content"       : "",
    "thumbnail_url" : "",
    "author_id"     : "",
    "created_date"  : "",
}
]

POST: /articles

data:
{       
    "title"         : "",
    "author_id"     : "",
    "content"       : "",
    "thumbnail_url" : "",
    "author_id"     : "",
    "created_date"  : ""
}

response:
true    // if success
false   // if failure



PUT: /articles

data:
[
{      
    "id"            : "", 
    "author_id"     : "",
    "title"         : "",
    "content"       : "",
    "thumbnail_url" : "",
    "author_id"     : "",
    "created_date"  : ""
}
]

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
