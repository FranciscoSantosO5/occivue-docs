---
title: "IDMR Reasoning"
taxonomy:
    category: docs
---

# IDMR — Intelligent Decision-Making Reasoning

IDMR is the decision/reasoning layer used around AI detections. Its purpose is to decide when a raw model output is sufficiently relevant to generate or escalate an operational event.

Current decision inputs can include:

- model probability;
- detected pixel/image area;
- persistence over time;
- category or importance of a monitored area.

This helps reduce operational noise compared with treating every raw detection as an immediate alarm.

IDMR is **not a guarantee of zero false alarms**. It is contextual decision logic that must be configured and validated for the use case.
