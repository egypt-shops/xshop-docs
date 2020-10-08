# PricingPlan Model

The PricingPlan DB Model specs

## Fields

| field | type       | status    | description           |
| ----- | ---------- | --------- | --------------------- |
| name  | Char       | optional  | PricingPlan's name    |
| price | MoneyField | Mandatory | The price of the plan |

## Methods

....

## Checklist

- [ ] A PricingPlan must be connected to a [Shop](shop.md)
