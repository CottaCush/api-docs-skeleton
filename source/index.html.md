---
title: <api_name> API Reference

language_tabs:

toc_footers:
  - <a href='https://github.com/tripit/slate'>Documentation Powered by Slate</a>

includes:
  - repositories
  - errors

search: true
---

# Introduction

Welcome to the <api_name>! You can use our API to access <api_name> endpoints.

# Authentication

> Sample Response

```json
{
   "status":"success",
   "data":{
      "access_token":"36a378c54edbdf61c4e004fa4c06f841ac6a3b57",
      "expires_in":21600,
      "token_type":"Bearer",
      "scope":null
   }
}
```

:api_name: uses OAUTH2 Authentication to allow access to the API. 

Clients are to request an `access_token` by calling the `/oauth/token` endpoint using assigned credentials. 

<aside class="notice">
It is expected than an <code>access_token</code> will be included in all API requests.
</aside>

### HTTP Request

`POST https://<base_url>/oauth/token`

### Headers
Parameter | Value
--------- | ------
Content-Type | application/x-www-form-urlencoded

### Post Parameters

Parameter | Default | Description
--------- | ------- | -----------
grant_type | client_credentials | Grant type - client_credentials
client_secret |  | Client OAUTH2 Secret
client_id |  | Client OAUTH2 ID


