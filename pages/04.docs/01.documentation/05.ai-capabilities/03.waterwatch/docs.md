---
title: "WaterWatch"
taxonomy:
    category: docs
---

# WaterWatch

WaterWatch is the OCCIVUE/AiAction visual-intelligence capability focused on water-related visual conditions such as visible flooding and abnormal water accumulation.

## Detection principle

WaterWatch applies computer-vision models to camera imagery. Detections can be combined with decision logic so probability, persistence, affected image area and monitored-zone relevance can influence whether an operational event is escalated.

WaterWatch is **visual detection**. It is not automatically a hydrological sensor, water-depth probe or hydraulic simulation model.

## Deployment factors

Performance depends on a stable view of the monitored zone. Reflections, glare, darkness, rain on the lens, shadows, vegetation, moving objects and scene changes can affect interpretation. Existing compatible IP cameras can potentially be reused.

## Edge monitoring and alerts

WaterWatch is suitable for continuous monitoring through OCCIVUE Edge. Current development work has included MQTT publication for fire/flood event scenarios when configured.

## Limitations

WaterWatch does not guarantee detection of every flood or water event and does not replace official warning systems, hydrological sensors, civil-protection procedures or engineering assessment. Exact minimum water depth, universal thresholds or accuracy percentages should only be used when a current release document defines them.
