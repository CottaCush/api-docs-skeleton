# Repositories

## Get All Respositories

> Response

```json
[
  {
    "id": 1,
    "name": "Yii2 Base Project",
    "key": "yii2-base-project",
    "status": "active"
  },
  {
    "id": 2,
    "name": "Phalcon Base Project",
    "key": "phalcon-base-project",
    "status": "active"
  },
  {
    "id": 2,
    "name": "Some Inactive Project",
    "key": "inactive-project",
    "status": "inactive"
  }
]
```

This endpoint retrieves all repositories.

### HTTP Request

`GET https://<base_url>/repositories`