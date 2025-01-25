# Hafiz Fabrics - Retail POS and ERP - architecture

A browser-based POS backed by Supabase, so the shop needs no server of its own. The schema is designed for fabric retail specifically - stock measured by length, priced per unit - rather than adapting a generic product-and-quantity model that does not fit how the goods are sold.

## Components

### POS interface

Sales entry and checkout

### Inventory

Length-based stock tracking

### Supabase backend

Postgres schema, authentication and API

### Reporting

Sales and margin views

## Stack

| Layer | Technology |
| --- | --- |
| Frontend | React, TypeScript, Vite |
| Styling | Tailwind CSS |
| Backend | Supabase (PostgreSQL) |
| Deployment | Static hosting |

Designed and implemented by Muhammad Tanveer - Full-Stack AI Automation Engineer.