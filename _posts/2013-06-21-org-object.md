---
layout: default
published: false
---

---
category: Organization
title: Organization Object
---

* *Organization* object has all the features of a *User* object, the only difference is instead of a *username* we have *orgname*.
An example object as shown below:

```{
    "orgname": "modilabs",
    "email": "modilabs@formhub.org",
    "name": "Modi Research Group",
    "city": "Nairobi",
    "country": "KE",
    "website": "http://buildafrica.org",
    "twitter": "@modilabs",
    "description": "maker of stuff",
    "gravatar": "",
    "require_auth": TRUE
}```

###Core Properties###
    
Each User has the following core properties:
    
* `orgname` - unique organization name identifier.
* `email` - Organization's email
* `name` - Name of the organization.
* `city` - City of organization
* `country` - Country of organization  
* `website` - Website of organization
* `twitter` - Twitter handle of organization
* `gravatar` - gravatar link
* `require_auth` - BOOLEAN, requires authentication to access forms via ODK Collect
