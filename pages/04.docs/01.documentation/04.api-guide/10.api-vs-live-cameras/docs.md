---
title: "API Calls vs Live Camera Monitoring"
taxonomy:
    category: docs
---

# API Calls vs Live Camera Monitoring

Use an OCCIVUE Platform API when your application needs **programmatic analysis of supported visual input**.

Continuous monitoring of many live RTSP cameras is normally an **OCCIVUE Edge** use case: streams are connected to local or near-site compute, inference runs continuously and event logic integrates into operational workflows.

Do not design a continuous multi-camera deployment by manually sending every frame to an API unless the current Platform release explicitly provides a documented streaming architecture for that purpose.
