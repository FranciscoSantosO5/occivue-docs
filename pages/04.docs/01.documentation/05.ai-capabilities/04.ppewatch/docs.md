---
title: "PPEWatch"
taxonomy:
    category: docs
---

# PPEWatch

PPEWatch is the OCCIVUE/AiAction product direction for visual monitoring of personal protective equipment in operational environments.

Potential classes can include items such as safety helmets and high-visibility clothing, but the exact supported classes must come from the current release documentation.

## Current status

PPEWatch is **under active development** and should not be treated as generally available unless a later release explicitly changes its status.

## Intended architecture

When production-ready, PPEWatch is intended to fit the same OCCIVUE architecture as other capabilities: continuous monitoring in an Edge-style deployment and possible Platform exposure when supported.

## Privacy and limitations

PPE detection requires imagery containing people. Detecting a person or PPE item is **not facial recognition** and does not imply that the system knows a person's name or employee identity.

Performance can be affected by camera angle, distance, resolution, lighting, occlusion, pose, clothing appearance and scene density. PPEWatch does not replace employer safety obligations, trained supervision or legally required procedures.
