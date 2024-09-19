---
date: 2024-09-19
title: Subtenant creation request with subdomain different than parent is not allowed
product_area: Platform services
change_type:
  - value: change-VSkj2iV9m
    label: Fix
component:
  - value: component-OG_650_b2
    label: Core platform
build_artifact:
  - value: tc-QHwMfWtBk7
    label: cumulocity
ticket: MTM-59299
version: 10.20.568.0
---
Previously, there was possibility to create subtenant with different subdomain than parent tenant from REST API level.
Now we are validating if domain of created subtenant is in subdomain of parent tenant.
