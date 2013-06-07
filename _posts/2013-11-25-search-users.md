---
category: Users
path: '/users/'
title: 'Search Users'
type: 'GET'
layout: nil
---

Get a list of users in the system.  Only admin can return all records. All other users must pass a property search/filter by.

###Request Parameters###

SORTING

* `sortAsc` - Sort ascending
* `sortDesc` - Sort descending

`/users?sortAsc={property1}`

Sorting is currently limited to one field

PAGINATION

* `limit` - Number of records to return in a result. Default = 25
* `offset` - Offset of the search result. Default = 0
* `limit=off` - Disables pagination. Pagination on by default.

`/users?limit=25&offset=50`

PARTIAL RESPONSE

* `fields` - specifies which fields should be returned in the response.

`/users?fields=name,email`

This would return just the specified properties of name, id and numBeds (in the properties sub-object) in a partial response. This is very helpful in optimizing performance in bandwidth constrained settings. All properties in the facility registry are accessible by this method including the core properties and those in the property sub-object.

FILTERING FACILITIES

* `{propertyName}` - name of the property you want to filter by

`/users?{propertyName}={filterValue}`

* Supports only exact matches of the filter value
* One value per instance of parameter
* Name of a parameter must exactly match the name of the property (core or extended) on which it filters data

FILTER BY UPDATED SINCE

* `updatedSince` - return users created/updated since a particular date expressed in ISO 8601 format.


Get the list of all Users in the system.


### Response ###

```Status: 200 OK```

`{
    "users": [
        {
            "username": "mberg",
            ...
        }
    ]
}`

Returns a list of [User object](#/user-object).
