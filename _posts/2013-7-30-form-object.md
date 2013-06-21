---
category: Forms
title: Form Object
layout: nil
---

The _Form_ object.

```{
    "formid": 1, 
    "id_string": "exp_two", 
    "sms_id_string": "exp_two", 
    "title": "Expenses Form 1.0", 
    "owner": "mberg", 
    "xls": "mberg/xls/exp_two.xls", 
    "json": "{ ... }", 
    "description": "", 
    "xml": "<?xml version=\"1.0\" encoding=\"utf-8\"?>\n<h:html> ... </h:html>", 
    "public": false, 
    "public_data": false, 
    "downloadable": true, 
    "is_crowd_form": false, 
    "allows_sms": false, 
    "encrypted": false, 
    "date_created": "2013-06-21T04:46:38.381", 
    "date_modified": "2013-06-21T04:46:38.381",
    "uuid": "361b8e1d9db84fecb2a37e08c50bdfb7", 
    "bamboo_dataset": ""
}
```
### Identifiers

* ***:formid***: A unique Formhub-wise identifier used for internal interactions.
* ***:id_string***: An owner-scope unique identifier based on file name used for user-level interactions (ODK, etc).


#### Form

* **id_string** - unique name of the form
* **title** - form title (64 chars)
* **uuid** - global unique uuid
* **date_created**
* **date_modified**

#### Form Details

* **public** - boolean
* **has_start_time** - form has a field called start
* **xlsform** - path to xlsform
* **json** - json form (json string). Make this into a seperate endpoint
* **xml** - xform
* **xform_hash**
* **crowd_form (is_crowd_form)** - boolean
* **downloadable (boolean)** - are we using this?
* **can_be_replaced (boolean)** - has no submissions so safe to replace
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
