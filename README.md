# Cart Total Calculator

A simple JavaScript cart total calculator that computes a cart's subtotal, discount, tax, and final total.

This project is based on the [Cart Total Calculator project](https://roadmap.sh/projects/js-cart-total-calculator) from roadmap.sh.

## Features

- Calculate the subtotal for all cart items
- Apply a percentage discount
- Calculate tax after the discount is applied
- Return a formatted cart summary

## Requirements

- [Node.js](https://nodejs.org/) 12 or later

## How to Run

Clone the repository, open the project directory, and run:

```bash
node cartTotalCal.js
```

The script prints cart summaries and subtotal examples to the console.

## Example

```javascript
const items = [
  { name: 'Notebook', price: 10, quantity: 2 },
  { name: 'Pen', price: 2, quantity: 5 },
];

createCartSummary(items, 10, 5);
```

The returned summary includes:

```javascript
{
  subtotal: '30.00',
  discount: '3.00',
  tax: '1.35',
  total: '28.35'
}
```

## Project Structure

```text
.
├── cartTotalCal.js
└── README.md
```
