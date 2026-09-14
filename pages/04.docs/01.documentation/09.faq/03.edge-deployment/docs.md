---
title: "Edge & Deployment FAQ"
taxonomy:
    category: docs
---

# Edge & Deployment FAQ

## Can OCCIVUE Edge use existing cameras?
Potentially yes. Reuse depends on stream access, codec, network, credentials, image quality, field of view and the selected capability.

## Is Edge limited to AXIS cameras?
No. AiAction has strong AXIS integration experience, while the newer direction is camera-agnostic and uses common IP-video mechanisms such as RTSP, with ONVIF/VAPIX where appropriate.

## Does Edge work without the Internet?
Local processing reduces dependence on continuous cloud inference, but remote alerts, monitoring, integrations, updates or other functions can still require connectivity.

## How many cameras can one Edge device support?
There is no universal documented number. Sizing depends on resolution, frame rate, modules, inference frequency, hardware and latency targets.

## Does Edge store video?
There is no universal documented storage/retention rule. Data handling depends on the deployment and current policy.

## Can Edge publish events to MQTT?
MQTT event publication has been implemented in current AiAction work for applicable use cases. Exact broker, topics, credentials and payloads are deployment-specific.
