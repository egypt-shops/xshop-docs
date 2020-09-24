# User login API Endpoint

## Specs

### Path: `/users/login`

### Method: `POST`

### Query Parameters

None

### Request

| field    | type         | status    | description          |
| -------- | ------------ | --------- | -------------------- |
| mobile   | Phone Number | mandatory | User's mobile number |
| password | string       | mandatory | User's password      |

### Response

**Code 200:** Successful login, following body returned

| field | type   | status    | description                             |
| ----- | ------ | --------- | --------------------------------------- |
| token | string | mandatory | token to be used for further operations |

**Code 400:** Invalid login, error messages returned

## Business Logic Checklist

- [ ] A user must be registered on the system to log in
- [ ] Return a Token for the user after a successful login
