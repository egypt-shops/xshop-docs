# Product Model

The Product DB Model specs

## Fields

| field   | type        | status    | description (verbose name) |
| ------- | ----------- | --------- | -------------------------- |
| name    | Char        | mandatory | Product's name             |
| barcode | PhoneNumber | mandatory | Product's BarCode          |
| qr_code | PhoneNumber | mandatory | Product's QR Code          |
| stock   | Int         | mandatory | How many in stock          |
| price   | Money       | mandatory | Product's Price            |

## Methods

....

## Business Logic Checklist

- [ ] A Product should be connected to a [Shop](02_shop.md)
- [ ] A Product must be searchable using a Bar Code
- [ ] A Product must be searchable using a QR code
- [ ] A Product can be added/edited by [ShopAdmin](03_shop_admin.md) & [DataEntryClerk](04_data_entry_clerk.md) Users only
