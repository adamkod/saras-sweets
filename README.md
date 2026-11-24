# Sara's Lebanese Sweets

A simple order page for Sara's homemade Lebanese desserts (pickup in Corona, CA).

Everything lives in `index.html`. Settings are in the `CONFIG` block near the top of the script:

- `ORDER_EMAIL`: where orders are emailed (through FormSubmit.co)
- `SMS_EMAIL`: email to text address that gets a copy of each order as a text
- `LEAD_DAYS`: minimum days of notice for an order
- `PREVIEW`: `true` means nothing is sent; set to `false` to take real orders
