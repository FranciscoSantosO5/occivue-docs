---
title: "Local Processing and Connectivity"
taxonomy:
    category: docs
---

# Local Processing and Connectivity

Edge camera streams are processed on local compute infrastructure close to the monitored environment. This reduces the need to continuously transmit every frame to a remote inference service.

Local inference may continue through an Internet interruption when the camera stream and local software remain available. However, a complete deployment may still need network connectivity for remote alerts, synchronisation, software updates, monitoring, MQTT/HTTP integrations or Platform-related services.

Therefore, **Edge reduces dependency on continuous cloud inference; it does not guarantee that every function works fully offline**.
