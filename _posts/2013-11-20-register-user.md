---
category: Users
path: /users/
title: Register User
type: POST
layout: nil
---

Register a new *User* in Formhub

### Request

Required parameters

**Payload**:

```{
	"username": "mberg",
	"name": "Matt Berg",
	"email": "mberg@formhub.org",
	"password": "letmein!"
}```

All other parameters in the [User object](#/user-object) can be passed optionally.


### Response

```Status: 201 Created```

For errors responses, see the [HTTP Response Codes](#/http-status).