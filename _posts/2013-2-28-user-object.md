---
category: Users
title: User Object
---

* `User` is used accross the API to represent a human taking an action (submitting a form, creating a project, etc).
* `User` is also used to identify API calls.
Bellow, an example of a returned `User` Object

```{
    "username": "mberg",
}```

###Core Properties###

Each User has the following core properties:

* `username` - Username (identifier) for that person.

`"username": "mberg"`

* `first_name` - First name of the user.

`"first_name": "Matt"`
