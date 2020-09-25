# Invoice Model

The Invoice DB Model specs

## Fields

| field      | type       | status    | description (verbose name)        |
| ---------- | ---------- | --------- | --------------------------------- |
| timestamps | datetime   | mandatory | Invoice's created/updated fields  |
| cashier    | FK         | mandatory | Cashier that created the invoice  |
| subtotal   | MoneyField | mandatory | Invoice's Subtotal (before taxes) |
| tax        | MoneyField | mandatory | Invoice's Taxes                   |
| total      | MoneyField | mandatory | total price                       |

## Methods

....

## Business Logic Checklist

- [ ] An Invoice must be connected to a [Shop](shop.md)
- [ ] An Invoice must be connected to a [Cashier](cashier.md)
- [ ] An Invoice can be added by [Cashier](cashier.md) Users only
- [ ] Taxes must be calculated based on ProductItem
- [ ] On Invoice Creation ProductItems must be deducted from the stock
