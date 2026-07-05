# Dataset Relationships
```text
Suppliers
│
├── Purchase Orders Header
│      │
│      └── Purchase Orders Lines
│
Products
│
├── Inventory Master
│
├── Stock Ledger
│
└── Sales Orders Lines
        │
Sales Orders Header
        │
Customers
        │
Invoices
        │
Payments

Branches are associated with inventory, purchases, and sales.
```