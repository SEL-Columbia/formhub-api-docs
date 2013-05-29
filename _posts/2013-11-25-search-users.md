---
category: Users
path: '/users/'
title: 'Search for Users'
type: 'GET'
layout: nil
---

Get the list of all Users in the system.

### Request

* (pagination?)

### Response

```Status: 200 OK```

`{
    "users": [
        {
            "username": "mberg",
            ...
        }
    ]
}`

Returns a list of [User object](#/user-object).
