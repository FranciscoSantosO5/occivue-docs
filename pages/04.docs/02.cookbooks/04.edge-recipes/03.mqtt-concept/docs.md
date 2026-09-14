---
title: "Publish an Event to MQTT — Integration Checklist"
taxonomy:
    category: docs
---

# Publish an Event to MQTT — Integration Checklist

MQTT event publication exists in current AiAction development work for applicable fire/flood scenarios.

Before implementation, obtain the deployment-specific integration documentation and confirm:

1. broker address;
2. transport/security configuration;
3. authentication method;
4. authorised topic structure;
5. event payload schema;
6. quality-of-service requirements if defined;
7. subscriber access controls;
8. retry/offline behaviour.

No executable MQTT example is included here because topic names, credentials and payload fields are deployment-specific and are not defined in the general knowledge base.
