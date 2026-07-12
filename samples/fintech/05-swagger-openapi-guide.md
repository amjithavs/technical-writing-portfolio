# Swagger/OpenAPI Guide

**Document ID:** API-002  
**Version:** 1.0  
**Status:** Draft (Portfolio Sample)

---

# Purpose

This guide explains how the FinCore Platform documents REST APIs using the OpenAPI Specification (OAS) and Swagger. It provides guidance for API consumers and developers on understanding, testing, and maintaining APIs.

> **Note:** This document is a fictional portfolio sample created to demonstrate API documentation and developer portal documentation skills.

---

# What is OpenAPI?

The OpenAPI Specification (OAS) is a standard format for describing REST APIs.

Benefits include:

- Interactive API documentation
- Standardized API definitions
- Automatic SDK generation
- API testing
- Easier developer onboarding

---

# API Documentation Workflow

```text
API Design
      │
      ▼
OpenAPI Specification
      │
      ▼
Swagger UI
      │
      ▼
Developer Portal
      │
      ▼
Customer Integration
```

---

# API Documentation Components

| Component | Description |
|-----------|-------------|
| OpenAPI Specification | Defines API endpoints and schemas |
| Swagger UI | Interactive API documentation |
| Request Examples | Sample API requests |
| Response Examples | Sample API responses |
| Error Codes | Standard HTTP error responses |

---

# Authentication

All APIs require OAuth 2.0 authentication.

Example:

```http
Authorization: Bearer <access_token>
```

---

# Sample Endpoint

### Get Customer Details

```http
GET /customers/{customerId}
```

### Path Parameter

| Parameter | Description |
|-----------|-------------|
| customerId | Unique customer identifier |

### Sample Response

```json
{
  "customerId": "100245",
  "firstName": "John",
  "lastName": "Smith",
  "status": "ACTIVE"
}
```

---

# API Versioning

API versions are managed using the URL path.

Example:

```text
/v1/customers
/v2/customers
```

Major versions introduce breaking changes, while minor updates remain backward compatible.

---

# Best Practices

- Use consistent endpoint naming.
- Provide request and response examples.
- Document all parameters.
- Include HTTP status codes.
- Maintain version history.
- Validate OpenAPI specifications before publishing.

---

# Benefits

Using OpenAPI provides:

- Faster API adoption
- Improved developer experience
- Consistent documentation
- Easier API maintenance
- Standardized integrations

---

# Related Documentation

- Banking Platform Overview
- Interface Specification
- REST API Guide
- Kafka Streaming Guide
