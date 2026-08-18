# Inventory Alert + Restock Agent

**Watches Shopify inventory, alerts owner when stock drops below threshold, recommends suppliers.**

- **Target:** Shopify stores with 50+ products
- **Price:** PKR 40,000 setup + PKR 5,000/month

## What It Does

Every 6 hours, checks all Shopify product inventory. When stock drops below 5 units, sends an email alert with restock recommendations powered by Claude AI, including suggested suppliers.

## Build Plan

| Day | Task |
|-----|------|
| 1 | Set up n8n workflow + Shopify connection |
| 2 | Add Claude intelligence for restock recommendations |
| 3 | Add email notification |
| 4 | Polish + Test end-to-end |

## Structure

```
inventory-alert-restock-agent/
├── workflow.json          # n8n workflow export
├── README.md
└── .gitignore
```