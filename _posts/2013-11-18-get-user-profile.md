---
category: Users
path: /users/:username
title: Get User Profile
type: GET
layout: nil
---

Get a particular _User_'s profile

### Request

* `username`: Username of the _User_ to display the Profile for.

### Response

```Status: 200 OK```

```{
	"username": "mberg",
	"first_name": "Matt",
	...
}```

The result body contains a single [User Object](#/user-object).

#### Errors

* ```Status: 404 Not Found```: _User_ object not found or unavailable

For errors responses, see the [HTTP Response Codes](#/http-status).