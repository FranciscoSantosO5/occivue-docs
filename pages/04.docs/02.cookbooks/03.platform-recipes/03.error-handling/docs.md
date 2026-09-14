---
title: "Handle Common HTTP Failures"
taxonomy:
    category: docs
---

# Handle Common HTTP Failures

Use this flow as a general diagnostic pattern:

```text
400 -> validate request against current schema
401 -> verify documented authentication and credential
403 -> verify product/subscription permission
404 -> verify current version and route
429 -> inspect current quota/rate-limit documentation
```

Do not hard-code a retry interval for `429` unless the current OCCIVUE API reference defines one.
