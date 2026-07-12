# API Style Guide

**Document ID:** API-STYLE-001  
**Version:** 1.0  
**Status:** Portfolio Sample

---

# Purpose

This guide defines the writing standards for documenting REST APIs in the FinCore Platform. Consistent API documentation improves developer experience, reduces ambiguity, and ensures maintainable documentation.

> **Note:** This is a fictional portfolio sample created to demonstrate API documentation standards.

---

# Naming Conventions

- Use nouns for resource names.
- Use lowercase URLs.
- Use plural resource names.

Example:

```
/customers
/accounts
/products
```

Avoid:

```
/GetCustomer
/CreateAccount
```

---

# HTTP Methods

| Method | Usage |
|---------|------|
| GET | Retrieve resources |
| POST | Create resources |
| PUT | Update resources |
| PATCH | Partial update |
| DELETE | Delete resources |

---

# Request Examples

Every endpoint must include:

- Description
- Parameters
- Sample Request
- Sample Response
- Error Codes

---

# Response Format

Successful responses should follow a consistent structure.

```json
{
  "status": "SUCCESS",
  "data": {},
  "message": "Operation completed successfully."
}
```

---

# Error Format

```json
{
  "status": "ERROR",
  "errorCode": "INVALID_REQUEST",
  "message": "Customer ID is required."
}
```

---

# Status Codes

| Code | Meaning |
|------|---------|
| 200 | Success |
| 201 | Created |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |
| 409 | Conflict |
| 500 | Server Error |

---

# Documentation Standards

Every API must include:

- Purpose
- Authentication
- Parameters
- Request example
- Response example
- Error responses
- Related APIs

---

# Best Practices

- Keep examples realistic.
- Document all parameters.
- Use consistent terminology.
- Update documentation with every API change.
