# Ansible Design Decisions

## Why Configuration Management
Configuration management is used to ensure hosts remain in a known-good state throughout their lifecycle.

## Role-Based Structure
Roles are used to:
- Encapsulate responsibility
- Enable reuse
- Reduce blast radius of changes

## Environment Separation
Separate inventories are maintained to:
- Validate changes safely
- Reduce production risk
- Support staged rollouts

## Safety Considerations
- Playbooks are designed for incremental application
- Changes are reviewed before execution
- Rollbacks are documented where applicable

## Patching Strategy

Patching is performed using controlled rollouts to:
- Limit blast radius
- Detect failures early
- Allow intervention before widespread impact

Serial execution and failure thresholds are used to enforce safety.

