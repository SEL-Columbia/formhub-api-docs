---
category: Projects
path: /projects/:owner
title: Create Project
type: POST
layout: nil
---

Create *Project* owned by ***:owner*** (*User* or *Org*)

### Request Payload

```{
    "name": "demo project", 
}```

### Response

```Status: 201 Created
Location: https://api.formhub.org/v1/projects/modilabs/1
```

*Project* [object](#/project-object)
