---
order: 2
slug: leakscope
title: LeakScope
summary: Automated external security scanner for modern web applications.
role: Founder and Full-stack Engineer
timeline: MARCH 2026 - PRESENT
year: "2026"
outcome: Built a scanner pipeline that inspects live surfaces without credentials, validates authentication and access patterns, and reports exploitable findings with remediation context.
image: /projects/LeakScope1.png
challenge: Security issues in production apps are often exposed through public assets and configuration drift, but teams rarely have continuous external checks.
solution: Built a scanner pipeline that inspects live surfaces without credentials, validates authentication and access patterns, and reports exploitable findings with remediation context.
impact:
  - 1,800+ applications scanned
  - 12,000+ vulnerabilities identified
secondaryLink: https://www.producthunt.com/products/leakscope
secondaryLabel: Product Hunt
stack:
  - Express
  - React
  - Supabase
  - WebSocket
  - Node.js
  - Redis
  - Vite
  - Tailwind CSS
link: https://leakscope.tech
---

## Overview

LeakScope is an external security scanner that looks for exposed issues from the public internet without needing credentials.

## Problem

Security reviews are often periodic and manual. Public assets, exposed configuration, and access-control mistakes can stay live for too long because nobody is checking them continuously.

## Approach

I focused on recurring signals in modern web apps:

- leaked secrets in bundled assets
- weak authorization around public endpoints
- JWT handling mistakes
- accidental exposure through configuration drift

The scanner is split into a few focused stages:

- collection of public assets and endpoints
- normalization and fingerprinting of findings
- rule-based analysis for auth and exposure issues
- report generation with remediation context

## Result

The output is a scanner that gives teams evidence, not just alerts, so findings are easier to act on.
