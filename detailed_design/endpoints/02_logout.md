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

**Code 200:** Logged out successfully

**Code 400:** Invalid logout, error messages returned

## Business Logic Checklist

- [ ] A user must be signed-in to logout
- [ ] A user must be authenticated to use this endpoint
- [ ] User's Token/Session gets deleted/expired after successful logout
- [ ] etc..
