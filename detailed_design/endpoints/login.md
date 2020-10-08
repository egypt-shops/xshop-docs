# User login API Endpoint

## Specs

### Path: `api/users/login`

### Method: `POST`

### Query Parameters

None

### Request

| field    | type         | status    | description          |
| -------- | ------------ | --------- | -------------------- |
| mobile   | Phone Number | mandatory | User's mobile number |
| password | string       | mandatory | User's password      |

### Response

**Success, Code 200:** Successful login, following body returned

```JSON
{
  "token": "string_of_the_token_here",
  "user": {
    "name": "user's name",
    "mobile": "user's mobile",
    "email": "user's email",
    "type": "users type"
  }
}
```

**Failure, Code 4xx:** Invalid login, error messages returned based on the error

## Checklist

- [x] A user must be registered on the system to log in
- [x] Return a Token for the user after a successful login
- [ ] Return User's data
