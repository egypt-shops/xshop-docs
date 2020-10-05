# OrderItem Model

The OrderItem DB Model specs

## Fields

| field    | type | status    | description |
| -------- | ---- | --------- | ----------- |
| order    | FK   | mandatory | Order       |
| product  | FK   | mandatory | Product     |
| quantity | int  | mandatory | How many?   |

## Methods

- unit_price
- total_price
- total_taxes

## Business Logic Checklist

- [ ] A ProductItem must be connected to an [Order](order.md)
- [ ] Must be saved upon Order Creation
