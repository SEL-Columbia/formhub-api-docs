---
category: Organization
path: /orgs/:org
title: Profile of an Organization
type: GET
layout: nil
---

Get the profile of an *Organization*.

```{
    "org": "modilabs",
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
    
* `org` - unique organization name identifier.
* `email` - Organization's email
* `name` - Name of the organization.
* `city` - City of organization
* `country` - Country of organization  
* `website` - Website of organization
* `twitter` - Twitter handle of organization
* `gravatar` - gravatar link
* `require_auth` - BOOLEAN, requires authentication to access forms via ODK Collect
