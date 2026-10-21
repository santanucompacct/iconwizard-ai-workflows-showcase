# Iconwizard AI Workflows Showcase

Public showcase for **Iconwizard AI**, a custom AI workflow automation initiative by Iconwizard Technologies Pvt. Ltd.

> From email to action—AI workflows built around your business.

## What we build

We design custom, AI-assisted workflows around each customer's actual processes—not a rigid, one-size-fits-all SaaS product.

Typical capabilities include:

- Reading purchase orders, invoices, agreements and other business documents
- Extracting and validating structured data
- Routing work to the correct person for approval
- Creating work orders or updating ERP/accounting systems
- Monitoring confirmations and follow-up emails
- Preparing invoices and payment reminders
- Connecting Gmail, Microsoft 365, Tally, ERP systems and custom MCP applications
- Preserving an auditable record of workflow actions

## First showcase: Email PO to invoice

The initial proof of concept demonstrates this controlled workflow:

1. A customer emails a purchase order.
2. AI reads the email and attached document.
3. The system extracts and validates the order details.
4. An authorised manager reviews and approves the order.
5. A work order is generated and assigned.
6. The assigned person confirms completion.
7. An invoice draft is prepared.
8. Accounts approves the invoice before it is emailed to the customer.

Financial and irreversible actions remain behind human approval.

## Repository structure

```text
demo/email-po-to-invoice/   Public interactive demonstration
workflow-templates/         Sanitised example workflow definitions
samples/                    Synthetic sample documents and outputs
docs/                       Public architecture and product notes
assets/                     Screenshots, diagrams and brand assets
```

Git does not store empty directories, so each initial directory contains a README placeholder.

## Public and private repositories

This repository contains only material suitable for public demonstration.

Production source code, live connectors, credentials, customer-specific configurations, customer documents and deployment details are maintained separately in a private repository.

## Planned website

The showcase is intended to support the Iconwizard AI website at **ai.iconwizard.in**.

## Security and privacy

All examples must use fictional or anonymised data. Never commit API keys, passwords, OAuth tokens, connection strings, production configuration or customer documents.

Please see [SECURITY.md](SECURITY.md) before reporting a security concern.

## Status

Initial structure and proof-of-concept planning.

## Licence

No open-source licence has been selected yet. Unless a licence is added, the contents are not granted for reuse or redistribution.
