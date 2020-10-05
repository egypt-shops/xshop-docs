# User Model

The User DB Model specs

## Fields (Table columns)

| field  | type        | status   | description (verbose name) |
| ------ | ----------- | -------- | -------------------------- |
| mobile | PhoneNumber | required | The user's mobile number   |
| name   | Char        | optional | user's name                |

## Methods

- `get_full_name`
- `get_short_name`
- `__str__` gets instance as string
- `__repr__` representation of instance in some contexts

## Business Logic Checklist

- [ ] A user must have a type (superuser, shop_manager, cashier, etc...) when created
- [ ] A Token must be generated on user creation
