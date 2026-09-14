---
title: "API Management Architecture"
taxonomy:
    category: docs
---

# API Management Architecture

The planned MVP uses an API-management layer to expose OCCIVUE services, control product/subscription access, enforce policies such as quotas or rate limits, and support a developer-facing portal.

**Azure API Management** has been selected in current technical planning as the core API-management layer. Gateway and policy functions are separated from the underlying OCCIVUE model or reasoning services.

Monitoring and usage visibility are part of the intended foundation, but the exact metrics available to an individual user depend on the implemented portal release.

> Exact policy values, authentication details, headers and subscription mechanics must be taken from the current production API documentation.
