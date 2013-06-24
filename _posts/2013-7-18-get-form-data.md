---
category: Forms
path: /forms/:formid/data
title: Get Form Data 
type: GET
layout: nil
---

This provides the JSON end point to submitted data.

### Request: Parameters

The parameters are specified using the mongodb syntax: http://www.mongodb.org/display/DOCS/Querying.

- *query*: query filter based on fields available in your form
- *count*: number of records to be returned by the api call
- *sort*: specify the field(s) to sort by, and how the ordering should be done
- *start*: start position within the record set
- *limit*: number of records to return
- *fields*: which fields in the data to return

E.g age parameter within the form
```
{query: {"age": {"$gte": "3"}}}
```

### Response

```
[
  {
    "name": "Mfangano st",
    "_submission_time": "2012-01-12T11:16:21",
    "age": "3",
    "_uuid": "1877e843734f4cbab664280879f9411b",
    "_geolocation": [
      "-1.2827019",
      "36.8248021"
    ],
    "_xform_id_string": "tutorial",
    "_status": "submitted_via_web",
    "_id": 22679,
    "gps": "-1.2827019 36.8248021 0.0 965.0"
  },
  {
    "picture": "1327317045573.jpg",
    "name": "Mama oliech ",
    "_submission_time": "2012-01-23T08:15:27",
    "age": "4",
    "_uuid": "409bb336ccff43c1982f8a1a6d3e85d7",
    "_attachments": [
      "ukanga/attachments/1327317045573.jpg"
    ],
    "_geolocation": [
      -1.2992095,
      36.7888088
    ],
    "_xform_id_string": "tutorial",
    "_status": "submitted_via_web",
    "_id": 22913,
    "gps": "-1.2992095 36.7888088 0.0 1290.0"
  }, ...
]
```
