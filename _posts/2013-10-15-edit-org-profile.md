---
category: Organization
path: /orgs/:orgname
title: Edit an Organization Profile
type: PUT
layout: nil
---

Change the data of an *Organization* Profile.

For example to update the website details of *Organization*

### Payload

```{
    "website": "www.mvpafrica.org"
}
```

### Response


```Status: 200 OK```

```{
    "orgname": "modilabs",
    "email": "",
    "name": "Modi Research Group",
    "city": "",
    "country": "",
    "website": "www.mvpafrica.org",
    "twitter": "",
    "description": "",
    "gravatar": "",
    "require_auth": false,
    "url": "http://api.formhub.org/v1/orgs/modilabs"
}```
