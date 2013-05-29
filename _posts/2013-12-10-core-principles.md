---
title: Core Principles

layout: nil
---
A few rules apply accross the API:
1. API calls require Authentication.
1. Authentication is based on the [_User_ Model](/#/user-object). Only _User_ can authenticate.
1. Exceptions to Authentication (registering _User_ for example) are marked **PUBLIC** in this document.