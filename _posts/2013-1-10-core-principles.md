---
title: Core Principles

layout: nil
---
A few rules apply accross the API:
1. API calls require Authentication.
1. Authentication is based on the [`User` Model](/#/user-object). Only `User` can authenticate.
1. Exceptions to Authentication (registering `User` for example) are marked **PUBLIC** in this document.