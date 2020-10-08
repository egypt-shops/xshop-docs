# Invoice Model

The Invoice DB Model specs

## Fields

| field      | type       | status    | description (verbose name)               |
| ---------- | ---------- | --------- | ---------------------------------------- |
| timestamps | datetime   | mandatory | Invoice's created/updated fields         |
| cashier    | FK         | mandatory | Cashier that created the invoice         |
| order      | FK         | mandatory | Order upon which this invoice is created |
| subtotal   | MoneyField | mandatory | Invoice's Subtotal (before taxes)        |
| tax        | MoneyField | mandatory | Invoice's Taxes                          |
| total      | MoneyField | mandatory | total price                              |

## Methods

....

## Checklist

- [ ] An Invoice must be connected to a [Shop](shop.md)
- [ ] An Invoice must be connected to a [Cashier](cashier.md)
- [ ] An Invoice must be connected to an [Order](order.md)
- [ ] An Invoice can be added by [Cashier](cashier.md) Users only or created for [Customer](customer.md) users only!
- [ ] Taxes must be calculated based on Products in the order
- [ ] Upon Invoice Creation Product's stock must be changed
