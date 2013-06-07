---
category: Users
title: User Object
---

* *User* is used accross the API to represent a human taking an action (submitting a form, creating a project, etc).
* *User* is also used to identify API calls.
Below, an example of a returned *User* Object

```{
    "username": "mberg",
    "email": "mberg@formhub.org",
    "name": "Matt Berg",
    "city": "Nairobi",
    "country": "KE",
    "organization": "Modi Research Group",
    "website": "http://buildafrica.org",
    "twitter": "@mberg",
    "description": "maker of stuff",
    "gravatar": "",
    "require_auth": TRUE
}```

###Core Properties###

Each User has the following core properties:

* `username` - Username (identifier) for that person.
* `email` - User's email
* `name` - Name of the user.
* `city` - City of user
* `country` - Country of user
* `orgnization` - Organization of user
* `website` - Website of user
* `twitter` - Twitter handle of user
* `gravatar` - gravatar link
* `require_auth` - BOOLEAN, requires authentication to access forms via ODK Collect


