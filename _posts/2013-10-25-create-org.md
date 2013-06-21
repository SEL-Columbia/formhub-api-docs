---
category: Organization
path: /orgs/
title: Create new Organization
type: POST
layout: nil
published: true
---

Create a new *Organization* object.

### Request

Required parameters

**Payload**:

```{
	"orgname": "modilabs",
	"name": "Modi Research Group"
}```

All other parameters in the [Organization object](#/org-object) can be passed optionally.


### Response

```
Status: 201 Created
Location: http://api.formhub.org/v1/org/modilabs
```

```{
    "org": "modilabs",
    "email": "",
    "name": "Modi Research Group",
    "city": "",
    "country": "",
    "website": "",
    "twitter": "",
    "description": "",
    "gravatar": "",
    "require_auth": false,
    "url": "http://api.formhub.org/v1/org/modilabs"
}```

For errors responses, see the [HTTP Response Codes](#/http-status).
