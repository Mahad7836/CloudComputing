# Identity and Access Management (IAM)

- Identity and Access Management
- Applies policies
- Defines who can do what with which resources

## Resource Hierarchy
- Organization
- Project
- Policies are inherited through the hierarchy

## Access Control
- Allow and deny policies
- Not easy to immediately remove access

# Cloud Identities

- Used to manage users and groups

# IAM Roles

## Basic Roles
- Broad access
- Affect all resources
- Viewer
- Editor
- Owner
- Billing Administrator

## Predefined Roles
- Designed for predefined actions

## Custom Roles
- Most companies follow least privilege
- Example: instance operator role
- Permissions must be managed
- Can be applied at project or organization level
- Cannot be applied at folder level


# Identity-Aware Proxy (IAP)

- User → IAP → ERP / CRM
- Performs authentication and authorization

# Best Practices

- Understand and leverage the resource hierarchy
- Grant roles to groups instead of individuals
