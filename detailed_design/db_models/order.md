# Order Model

The Order DB Model specs

## Fields

| field            | type     | status    | description (verbose name)              |
| ---------------- | -------- | --------- | --------------------------------------- |
| timestamps       | datetime | mandatory | ORder's created/updated fields          |
| cashier/customer | FK       | mandatory | Cashier/Customer that created the order |

## Methods

....

## Checklist

- [ ] An Order must be connected to a [Shop](shop.md)
- [ ] An Order must be connected to a [Cashier](cashier.md) or a [Customer](customer.md)
- [ ] An Order can be added by [Cashier](cashier.md) and [Customer](customer.md) Users only
