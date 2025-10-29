# Fundamental of computer security
## Identification , Authentication , and Authorization 
| Concept                 | Description                | Example
|-------------------------|----------------------------|----------------------------
| **Identification**      | Claming an identity        | Typing username
| **Authentication**      | Proving identity           | Entering password / fingerprint
| **Authorization**       | Granting access            | Accessing certain files after login 

## Key Principles
**Authentication Methods 
- knowledge-based: Password,PINs
- possession-based: smart cards, OTP tokens
- Inherence-based: Biometrics (fingerprint, face ID)
- Multifactor Authentication (MFA): Combination of 2 or more above
- Single sing-on (SSO): one time login across multiple system (e.g.,) Google or microsoft SSD)

# Authorization Models 
- DAC (Discretionary access control): Owner decides who can access (Windows permission)
- MAC (Mandatory Access Control): Access based on classification levels (military systems)
- RBAC (Role-Based Access Control): Permission assigned to roles (Admin , Manager , User)
- ABAC (Attributes-Based Access Control); Access based on condition (times, location, User type).

## Example:
An "HR Manager" role can view employee data, while "Employee" role can only view their own profile.

# Best Parctices
- user strong, unique passwords.
- Apply MFA wherever possible.
- Review role-bassed permissions regularly.
- Log all authentication and access events .
