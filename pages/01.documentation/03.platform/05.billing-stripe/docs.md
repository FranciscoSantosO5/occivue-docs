---
title: "Billing and Stripe"
taxonomy:
    category: docs
---

# Billing and Stripe

Stripe is included in the intended Platform MVP commercial workflow.

The planned architecture coordinates commercial status with API access using a pattern that can include:

- Stripe Checkout and billing events;
- webhook processing;
- an Azure Function or equivalent application layer;
- persistence that maps portal users, Stripe customers and API-management subscriptions;
- API-management administration calls to activate, suspend or update access.

These details describe the planned architecture. Billing, invoice and self-service subscription-management behaviours should only be treated as available once the corresponding production implementation is released.

Final prices, free quotas and billing cycles are not defined by the current knowledge source.
