---
category: Organization
path: /orgs/
title: Register new Organization
type: POST
layout: nil
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

```Status: 201 Created```

```{
    "orgname": "modilabs",
    "email": "",
    "name": "Modi Research Group",
    "city": "",
    "country": "",
    "website": "",
    "twitter": "",
    "description": "",
    "gravatar": "",
    "require_auth": false
}```

For errors responses, see the [HTTP Response Codes](#/http-status).
