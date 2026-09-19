# Hafiz Fabrics - Retail POS and ERP

> Point-of-sale and stock system for a fabric retailer, built on React, TypeScript and Supabase.

Built by **[Muhammad Tanveer](https://www.linkedin.com/in/muhammad-tanveer-advenno/)** - Full-Stack AI Automation Engineer.

[![Source](https://img.shields.io/badge/source-private%20repository-lightgrey)](#source-code-and-access) [![Role](https://img.shields.io/badge/built%20by-Muhammad%20Tanveer-blue)](https://github.com/haddindeve)

## Contents

- [The problem](#the-problem)
- [The approach](#the-approach)
- [Architecture](#architecture)
- [Tech stack](#tech-stack)
- [Key capabilities](#key-capabilities)
- [Results](#results)
- [FAQ](#faq)
- [Source code and access](#source-code-and-access)
- [About the engineer](#about-the-engineer)
- [Related projects](#related-projects)

## The problem

A fabric retailer tracked sales and stock on paper. Reconciling what sold against what remained meant counting, and pricing decisions were made without knowing actual margin per item.

## The approach

A browser-based POS backed by Supabase, so the shop needs no server of its own. The schema is designed for fabric retail specifically - stock measured by length, priced per unit - rather than adapting a generic product-and-quantity model that does not fit how the goods are sold.

## Architecture

| Component | Responsibility |
| --- | --- |
| **POS interface** | Sales entry and checkout |
| **Inventory** | Length-based stock tracking |
| **Supabase backend** | Postgres schema, authentication and API |
| **Reporting** | Sales and margin views |

## Tech stack

| Layer | Technology |
| --- | --- |
| Frontend | React, TypeScript, Vite |
| Styling | Tailwind CSS |
| Backend | Supabase (PostgreSQL) |
| Deployment | Static hosting |

## Key capabilities

- Point-of-sale checkout
- Length-based fabric inventory
- Sales and margin reporting
- Managed Postgres backend with no server to maintain

## Results

- Paper records replaced by live stock and sales figures
- Margin visible per item at the point of pricing

## FAQ

### Why Supabase?

It provides Postgres, auth and an API without the shop needing to run or maintain a server.

### How is fabric stock handled?

Stock is tracked by length rather than unit count, matching how fabric is actually bought and sold.

### Does it work on existing hardware?

It runs in the browser, so any reasonably modern machine or tablet works.

### Is the source public?

Private repository; access on request.

## Source code and access

This repository is the public case study for **Hafiz Fabrics - Retail POS and ERP**. The full implementation - application code, database schema, tests and deployment configuration - lives in a **private repository** on this account, alongside the rest of the work shown here.

Source access can be arranged for hiring conversations, technical review or client due diligence. The quickest route is a short message on [LinkedIn](https://www.linkedin.com/in/muhammad-tanveer-advenno/) or an email to [mtanveertahir6666@gmail.com](mailto:mtanveertahir6666@gmail.com).

## About the engineer

**Muhammad Tanveer - Full-Stack AI Automation Engineer**

Full-stack AI automation engineer. I build agentic systems, browser and workflow automation, RAG pipelines and the production web platforms they run on - from Rust and Python services to Next.js dashboards and PHP/MySQL business systems.

- GitHub: [haddindeve](https://github.com/haddindeve)
- LinkedIn: [Muhammad Tanveer](https://www.linkedin.com/in/muhammad-tanveer-advenno/)
- Email: [mtanveertahir6666@gmail.com](mailto:mtanveertahir6666@gmail.com)
- Location: Pakistan

## Related projects

- [Business OS - AI-Native Multi-Branch ERP](https://github.com/haddindeve/business-os-multi-branch-erp)
- [Lunaria - Privacy-First Women's Wellness App](https://github.com/haddindeve/lunaria-womens-wellness-app)
- [Doctern - AI Document OCR and Table Extraction](https://github.com/haddindeve/doctern-document-ocr-ai)
- [ARMenu - Augmented Reality Restaurant Menu SaaS](https://github.com/haddindeve/armenu-augmented-reality-menu-saas)
- [Crypto Trading Bot with Control Dashboard](https://github.com/haddindeve/crypto-trading-bot-dashboard)
- [Gym Management CRM with NFC Gate Control](https://github.com/haddindeve/gym-management-crm-system)

---

<sub>Hafiz Fabrics - Retail POS and ERP - case study by Muhammad Tanveer - Full-Stack AI Automation Engineer. Keywords: retail POS system, fabric shop software, inventory management POS, React TypeScript POS, Supabase application, small business ERP.</sub>