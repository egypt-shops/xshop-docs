# Logout API Endpoint

## Specs

### Path: `api/users/logout`

### Method: `POST`

### Query Parameters

None

### Headers

Key: `Authorization`, Value: `Token user's_token_here`

### Request

None

### Response

**Success, Code 200:**

```JSON
{"detail":"Logged out successfully"}
```

**Failure, Code 4xx:** Invalid logout, error messages returned based on the error

## Checklist

- [ ] A user must be signed-in to logout
- [ ] A user must be authenticated to use this endpoint
- [ ] User's Token/Session gets deleted/expired after successful logout
- [ ] etc..
