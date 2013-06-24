---
category: Projects
title: Project Object
layout: nil
---

### Specificities

* *Project* owned by an *Organization* can have members (*User*) & *Team*s.
* *Project* owner by a *User* can only have members (*User*).
* Ownership (**:ownerid**) can be hold by both *User* and *Organization*.
* *Collaborators* refers to members of the *Project*. A *Collabortor* is either a *User* or a *Team*.

### Project Object

```{
    "url": "https://api.formhub.org/v1/projects/modilabs/1", 
    "owner": "https://api.formhub.org/v1/users/modilabs", 
    "created_by": "https://api.formhub.org/v1/users/mberg", 
    "name": "demo project", 
    "date_created": "2013-06-24T05:26:57.857", 
    "date_modified": "2013-06-24T05:26:57.857"
}```

- *owner*: organization or user - org/username
- *created_by*: username of person creating the project
- *name*: name of project
- *url*: project id
- 
