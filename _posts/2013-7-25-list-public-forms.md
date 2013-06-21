---
category: Forms
path: /forms/public
title: List Public Forms
type: GET
layout: nil
---

Searchable list of all *Form* objects marked *public*.

### Response

```[{
    "formid": 1, 
    "id_string": "exp_two", 
    "sms_id_string": "exp_two", 
    "title": "Expenses Form 1.0", 
    "owner": "mberg", 
    "public": true, 
    "public_data": false, 
    "uuid": "361b8e1d9db84fecb2a37e08c50bdfb7", 
    ...
}, {
    "formid": 43, 
    "id_string": "good_eats", 
    "sms_id_string": "ge", 
    "title": "Good Eats 1.0", 
    "owner": "denno", 
    "description": "", 
    "public": true, 
    "public_data": true, 
    ...
}, ...
]
```
