---
name: api-rate-limit-guard
description: Implement and manage API usage limits to protect infrastructure.
---

# API Rate-Limit Guard

This skill prevents system abuse and ensures fair resource usage by limiting how often APIs can be called.

## Instructions

1. Implement rate-limiting logic (Token bucket, Sliding window).
2. Set up different limits for different user tiers (Free vs Pro).
3. Provide clear HTTP 429 error messages with 'Retry-After' headers.
4. Use Redis for fast, distributed limit tracking.
5. Monitor for 'Bursty' traffic and adjust limits dynamically.

## Examples

- "Add a rate limit of 10 requests per minute to my public API."
- "Implement a tiered rate-limiting system for my SaaS users."