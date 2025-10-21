# azure-rbac-management
Azure RBAC implementation with management groups, built-in roles, custom RBAC roles, and access monitoring using Azure Portal and Activity Log.


## Lab Overview

**AZ-104 Lab 02a: Manage Subscriptions and RBAC** - Complete implementation of Azure's role-based access control framework across four core tasks:

1. **Management Group Implementation** - Created hierarchical governance structure
2. **Built-in Role Assignment** - Applied VM Contributor role at management group scope  
3. **Custom Role Development** - Engineered least-privilege role with permission exclusion
4. **Access Monitoring** - Implemented Activity Log filtering for compliance tracking

## Key Technical Takeaways

### Management Group Architecture
- Designed `az104-mg1` management group for subscription hierarchy and policy inheritance
- Leveraged root management group for directory-level governance controls
- Implemented scope-based access control reducing administrative overhead

### RBAC Strategy & Implementation
- Applied principle of least privilege through custom role modification
- Excluded "Registers Support Resource Provider" permission from Support Request Contributor role
- Assigned roles to security groups (not individuals) for scalable access management

### Enterprise Governance
- Established management group-scoped role assignments for inheritance across subscriptions
- Implemented Activity Log monitoring with filtered views for audit compliance
- Demonstrated JSON role definition understanding for custom permission management

## Technical Skills Demonstrated

- **Azure Governance**: Management group hierarchy design and implementation
- **Access Control**: RBAC role assignment, custom role development, and permission management
- **Security Architecture**: Least privilege implementation and group-based access control
- **Compliance**: Activity Log analysis and audit trail establishment
- **Enterprise Design**: Scalable access management patterns for multi-subscription environments
