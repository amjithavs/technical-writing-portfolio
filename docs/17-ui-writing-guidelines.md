# UI Writing Guidelines

## Purpose

This guide defines best practices for writing clear, concise, and consistent user interface (UI) text. Well-crafted UI content improves usability, reduces confusion, and helps users complete tasks efficiently.

---

# Writing Principles

UI text should be:

- Clear
- Concise
- Action-oriented
- Consistent
- User-focused

---

# Tone of Voice

Use a tone that is:

- Professional
- Friendly
- Helpful
- Direct
- Positive

Avoid:

- Technical jargon
- Blameful language
- Long sentences
- Ambiguous wording

---

# Buttons

Use verbs that clearly describe the action.

| Avoid | Preferred |
|--------|-----------|
| Submit | Save |
| OK | Continue |
| Execute | Run Validation |
| Cancel Operation | Cancel |

---

# Form Labels

Use clear and descriptive labels.

| Poor | Better |
|------|--------|
| Name | Project Name |
| ID | Project ID |
| Config | Configuration Profile |

---

# Placeholder Text

Use placeholders to guide users.

Example:

```text
Enter the project name
```

Instead of:

```text
Project
```

---

# Error Messages

Error messages should:

- Explain what happened
- Explain why it happened (if known)
- Tell the user how to resolve it

### Example

❌ Poor

```text
Invalid Credentials
```

✅ Better

```text
The email or password you entered is incorrect.
Please try again.
```

---

### Example

❌ Poor

```text
Submission Failed
```

✅ Better

```text
We couldn't save your changes.
Please verify the required fields and try again.
```

---

# Success Messages

Confirm successful actions.

Examples:

- Project created successfully.
- Configuration updated successfully.
- Report generated successfully.

---

# Confirmation Messages

Example:

```text
Are you sure you want to delete this project?

This action cannot be undone.
```

---

# Empty States

Instead of displaying a blank page, provide helpful guidance.

Example:

```text
No projects found.

Create your first project to get started.
```

---

# Tooltips

Keep tooltips short.

Example:

```text
Validation Profile

Select a predefined validation configuration.
```

---

# Notifications

Use concise notifications.

Examples:

- Settings saved.
- Validation completed.
- Report exported.

---

# Accessibility

Ensure UI text:

- Uses meaningful labels
- Avoids abbreviations
- Is readable by screen readers
- Does not rely on color alone

---

# Terminology Standards

Use consistent terminology across the product.

| Preferred | Avoid |
|------------|-------|
| Sign In | Login |
| Project | Job |
| Save | Submit |
| User | Operator (unless role-specific) |
| Validation | Execution |

---

# Review Checklist

Before publishing UI text, verify:

- Grammar and spelling
- Consistent terminology
- Clear instructions
- Accessibility compliance
- Alignment with the product style guide

---

# Related Documentation

- Documentation Style Guide
- User Guide
- Administrator Guide
- Accessibility Guidelines
