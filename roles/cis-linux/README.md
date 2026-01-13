# CIS Linux Baseline Role

## Purpose
Applies a selected subset of CIS Linux Benchmark controls that provide
meaningful security improvements with minimal operational risk.

## Philosophy
This role intentionally avoids enforcing controls that:
- Break workloads
- Require application-specific tuning
- Reduce platform availability

## Scope
The role focuses on:
- File permission hardening
- Kernel parameter sanity
- Basic audit configuration

## Non-Goals
- Full CIS benchmark enforcement
- Host lockdown at the cost of operability
