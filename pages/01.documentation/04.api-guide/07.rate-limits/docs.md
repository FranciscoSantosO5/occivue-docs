---
title: "Rate Limits and Quotas"
taxonomy:
    category: docs
---

# Rate Limits and Quotas

The OCCIVUE Platform architecture is intended to enforce rate limits and/or quotas through its API-management layer.

Exact limits depend on the product and subscription configuration and are not defined in this general knowledge source.

HTTP `429` generally indicates that a request rate or quota has been exceeded. Exact OCCIVUE retry guidance and headers must come from the current API reference; do not assume a retry interval.
