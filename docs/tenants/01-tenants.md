# Tenants
Tenants are the customer of the application

# Tenants Journey
1. Tenants are the entity which uses the platform
2. Tenants have users who can access the features
3. Tenants Users can configure features

# Tenant Schema
- id  - String
- name - String
- email - String
- status - Enum

# Tenant Lifecycle
```
DRAFT   -> COMMISSIONED -> DECOMMISSIONED
        -> CANCELLED 
```

# Tenant Features
1. Create Tenant
2. Updated Tenant
3. Commission Tenant
4. Decommission Tenant