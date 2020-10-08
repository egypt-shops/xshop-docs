# Login

The login page for ordinary (non-admin) users

## Path: `/users/login`

## Design Elements

- A welcome message
- User Login form
  - Mobile
  - Password

## Checklist

- [ ] Available Publicly
- [ ] A user must be registered to login
- [ ] Errors are shown correctly in case of invalid login
- [ ] has a link in the [Home](home.md) page
- [ ] styled with django crispy forms (bootstrap4)
- [ ] redirects to:
  - [ ] [data_entry](data_entry.md) if user is data entry clerk
  - [ ] [pos](pos.md) if user is cashier
  <!-- - [ ] [dashboard](dashboard.md) if user is staff, manager or sub-manager -->
  - [ ] [Home](home.md) if user is customer
