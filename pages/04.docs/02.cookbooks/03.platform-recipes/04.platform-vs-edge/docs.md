---
title: "Choose Platform or Edge for a Video Workflow"
taxonomy:
    category: docs
---

# Choose Platform or Edge for a Video Workflow

## Platform pattern
Use when your software submits supported input and receives programmatic analysis results.

```text
application -> OCCIVUE Platform API -> structured result -> application workflow
```

## Edge pattern
Use when cameras must be monitored continuously near the site.

```text
live cameras -> OCCIVUE Edge -> model + reasoning -> event -> operational integration
```

If the requirement is “monitor many RTSP cameras continuously”, start with Edge unless the current Platform release explicitly documents a streaming API for that use case.
