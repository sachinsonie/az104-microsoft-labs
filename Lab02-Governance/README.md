# Lab 02 — Governance & RBAC

## What I Did
- Implemented Management Groups hierarchy
- Created custom RBAC role with specific permissions
- Assigned built-in and custom RBAC roles at different scopes

## Key Learnings
- Owner = everything + assign roles
- Contributor = manage resources, cannot assign roles
- Reader = view only
- Roles are inherited downward through scope hierarchy
- Deny assignments ALWAYS win over any Allow role
- Management Groups max depth = 6 levels
- Custom roles per tenant = max 2000

## Exam Tips
- RBAC controls WHO can act
- Azure Policy controls WHAT is allowed
- Role assigned at Management Group = inherited by all subscriptions under it
