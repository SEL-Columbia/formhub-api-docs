---
category: Forms
title: Form Object
layout: nil
---

The _Form_ object.

```{
    "id": "361b8e1d9db84fecb2a37e08c50bdfb7", 
    "url":https://api.formhub.org/v1/forms/361b8e1d9db84fecb2a37e08c50bdfb7",
    "id_string": "exp_two", 
    "title": "Expenses Form 1.0", 
    "owner": "https://api.formhub.org/v1/users/mberg", 
    "description": "",
    "active": true,
    "form_public": false, 
    "data_public": false, 
    "crowd_form": false, 
    "allows_sms": false, 
    "sms_id_string": "exp_two", 
    "encrypted": false, 
    "date_created": "2013-06-21T04:46:38.381Z", 
    "date_modified": "2013-06-21T04:46:38.381Z",
    "bamboo_dataset": ""
}
```
### Identifiers

* ***:formid***: A unique Formhub-wise identifier used for internal interactions.
* ***:id_string***: An owner-scope unique identifier based on file name used for user-level interactions (ODK, etc).


#### Form

* **id_string** - unique name of the form
* **title** - form title (64 chars)
* **id** - global unique form uuid
* **date_created**
* **date_modified**

#### Form Details

* **public** - boolean
* **has_start_time** - form has a field called start
* **crowd_form (is_crowd_form)** - boolean
* **active (boolean)** - form is accessible for download in mobile clients
* **description** - form description
* **encrypted (boolean)** - submissions are encrypted.
* **cloned** - path to original form


#### Data Details

* submission_count
* has_geopoints (boolean)
* last_submission
* submission_modification
* public_data - boolean
* license - no license, cc, share-alike
* SMS
** sms_form (change from allows_sms) (boolean) - form is valid sms form
** sms_id_string -
* bamboo_dataset
** url
* rest_service: `[{name: “JSON POST”, url: http://bamboo.io}]`
* media: `[{name: “bird.jpg”, “url”: http://yahoo.com/bird.jpg”}]`
* mapbox
** name
** url
** jsonp
* supporting_docs (url)
* source_docs (url)
* permissions
** user
** type: view, edit
