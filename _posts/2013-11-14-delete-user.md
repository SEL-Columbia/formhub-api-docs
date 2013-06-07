---
category: Users
path: /users/:username
title: Delete User
type: DELETE
layout: nil
---

Delete *User* account and all its associated data


### Request

* **`{user}`** of the user to delete.
* **The body is omitted**.

### Response

If the user is found and deleted

`Status: 200 OK`

```{
    code: 200,
    id: 'mberg'
    message: 'User deleted'
}```

If facility resource for id is not found

```Status: 404 Not Found```
```{
    code: 404 Not Found,
    message: 'User not found'
}```

For errors responses, see the [response status codes documentation](#http-response-codes).