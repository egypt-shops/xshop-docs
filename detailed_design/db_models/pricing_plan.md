# PricingPlan Model

The User DB Model specs

## Fields

| field | type       | status    | description           |
| ----- | ---------- | --------- | --------------------- |
| name  | Char       | optional  | user's name           |
| price | MoneyField | Mandatory | The price of the plan |

## Methods

....

## Business Logic Checklist

- [ ] A PricingPlan must be connected to a [Shop](shop.md)
