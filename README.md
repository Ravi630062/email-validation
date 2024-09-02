Syntax Validation

1. Check for the presence of a local part (before the @)
2. Check for the presence of a domain (after the @)
3. Check for the presence of a top-level domain (TLD)
4. Validate the local part:
    - Allow letters (a-z, A-Z)
    - Allow numbers (0-9)
    - Allow special characters (._%+-)
    - Do not allow consecutive dots (..)
5. Validate the domain:
    - Allow letters (a-z, A-Z)
    - Allow numbers (0-9)
    - Allow hyphens (-)
    - Do not allow consecutive hyphens (--)
6. Validate the TLD:
    - Check against a list of valid TLDs

Domain Validation

1. Check if the domain has a valid MX record
2. Check if the domain has a valid A record
3. Check if the domain is not a disposable email address
4. Check if the domain is not a role-based email address (e.g., info@, support@)

Disposable Email Detection

1. Check against a list of known disposable email providers
2. Check for common disposable email address patterns

Role-Based Email Detection

1. Check for common role-based email address patterns (e.g., info@, support@)

Additional Checks

1. Check for email address length (should be between 3 and 254 characters)
2. Check for leading or trailing whitespace
3. Check for consecutive dots (..) in the local part or domain
