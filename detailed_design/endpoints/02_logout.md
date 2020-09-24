# Logout API Endpoint

## Specs

### Path: `/users/logout`

### Method: `POST`

### Query Parameters

None

### Request

| field | type   | status    | description                 |
| ----- | ------ | --------- | --------------------------- |
| token | string | mandatory | User's authentication token |

### Response

**Success, Code 200:**

```JSON
{"detail":"Logged out successfully"}
```

**Failure, Code 4xx:** Invalid logout, error messages returned based on the error

## Business Logic Checklist

- [ ] A user must be signed-in to logout
- [ ] A user must be authenticated to use this endpoint
- [ ] User's Token/Session gets deleted/expired after successful logout
- [ ] etc..
