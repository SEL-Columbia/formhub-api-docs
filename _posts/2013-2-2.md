---
category: Users
path: '/users/'
title: 'Search for Users'
type: 'GET'

layout: nil
---

Get the list of all Users in the system.

### Request
<!-- * **`{id}`** of the facility -->

### Response

```Status: 200 OK```

`{
   "facility": {
   "name": "Kakamega HC",
   ...
}`

Returns the [facility object](#facility-resource) matching **`{id}`** including core and extended properties.

```Status: 404 Not Found```
```{
    code: 404 Not Found,
    message: 'Resource not found'
}```

Facility resource not found or unavailable

For errors responses, see the [response status codes documentation](#response-status-codes).
