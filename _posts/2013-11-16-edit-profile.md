---
category: Users
path: /users/:username
title: Update User
type: PUT
layout: nil
---

Update the user, replacing the user properties with the new resource representation passed in the request.

### Request

* Full new resource representation of the user (not a partial update)
* **The body can't be empty** and must include at least the name attribute, a `string` that will be used as the name of the user.
* The `id`, `url`, `createdAt`, and `updatedAt` core properties cannot be changed by the client.  An update request including any of these properties or any unknown core properties should result in a `400 Bad Request` error.

```{
    name: 'Matt Berg'
}```

### Response

Returns the location of the updated user.

`Status: 200 OK
Location: https://api.formhub.org/v1/users/mberg`

`{
   "users": {
   "name": "Matt Berg",
   ...
}`

Returns the [user object](#user-resource) of the updated facility.

*Not Found*

If the the facility resource is not found to update

```Status: 404 Not Found```
```{
    code: 404 Not Found,
    message: 'Resource not found'
}```