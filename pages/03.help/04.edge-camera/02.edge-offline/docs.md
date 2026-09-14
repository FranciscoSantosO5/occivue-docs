---
title: "Edge Device Offline"
taxonomy:
    category: docs
---

# Edge Device Offline

Separate the problem into layers:

1. device power and operating-system availability;
2. OCCIVUE local process/container status;
3. local network state;
4. camera reachability;
5. external/Internet connectivity;
6. remote alert or integration endpoints.

Do not assume an Internet outage is the only cause. Local inference can be separate from remote connectivity, depending on the deployment.
