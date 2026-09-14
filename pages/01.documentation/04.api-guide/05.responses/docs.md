---
title: "Responses"
taxonomy:
    category: docs
---

# Responses

Depending on the API, a response may contain information such as:

- detected class;
- model confidence;
- image-coordinate information;
- reasoning or event information.

Exact response field names, confidence scales, bounding-box coordinate formats and error schemas are defined by the current OpenAPI/API reference for the specific endpoint.

Do not build against guessed JSON fields or examples from a different API version.
