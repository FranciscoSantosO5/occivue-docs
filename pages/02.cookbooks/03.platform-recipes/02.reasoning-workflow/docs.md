---
title: "Add Reasoning to Model Output — Conceptual"
taxonomy:
    category: docs
---

# Add Reasoning to Model Output — Conceptual

IDMR-style reasoning can evaluate raw model output using operational context such as probability, apparent detection area, persistence and monitored-zone category.

## Conceptual flow

```text
visual_input
  -> model_inference
  -> collect_context
  -> evaluate_probability
  -> evaluate_detected_area
  -> evaluate_persistence
  -> evaluate_zone_importance
  -> create_or_suppress_event
```

The exact OCCIVUE reasoning API, request fields and thresholds must come from the current Platform/API documentation. There is no universal confidence threshold appropriate for every module or scene.
