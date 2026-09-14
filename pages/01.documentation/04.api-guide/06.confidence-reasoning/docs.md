---
title: "Confidence and Decision Logic"
taxonomy:
    category: docs
---

# Confidence and Decision Logic

A model confidence score is a model output. It is **not a guarantee** that the real-world event is present.

In operational deployments, OCCIVUE/AiAction can combine raw model output with IDMR decision rules such as:

- probability;
- detected pixel/image area;
- persistence over time;
- category or importance of the monitored area.

There is no universal confidence threshold that is correct for every module or scene. Threshold guidance should come from module-specific documentation or deployment validation.
