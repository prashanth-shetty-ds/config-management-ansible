# Configuration Management – Ansible

## Overview
This repository contains configuration management automation used to enforce
consistent operating system, security, and platform baselines across
infrastructure supporting the SRE Platform Lab.

The focus of this repository is **safe, auditable, and repeatable automation**,
not ad-hoc scripting.

## Design Principles
- Idempotent execution
- Clear separation of concerns
- Environment-specific configuration
- Version-controlled change management
- Human-readable automation

## Scope
This repository manages:
- OS baseline configuration
- Security hardening
- Time synchronization
- Logging and monitoring agents
- Certificate and secret lifecycle support

## Non-Goals
- Application deployment
- One-off emergency fixes
- Environment-specific hacks

## Relationship to Platform
This repository implements the automation model defined in the
`sre-platform-lab` repository and is consumed by platform operators.

## Author
Prashanth Shetty  
Senior Cloud / SRE Engineer
