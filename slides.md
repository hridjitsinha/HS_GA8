---
marp: true
theme: default
paginate: true
footer: '23f2004319@ds.study.iitm.ac.in'
style: |
  section {
    background-color: #ffffff;
    color: #333;
  }
  h1 {
    color: #0066cc;
  }
---

# API Documentation

Simple Product Documentation Guide

**Contact**: 23f2004319@ds.study.iitm.ac.in

---

## Getting Started

This documentation covers our REST API with simple examples.

---

## Authentication

Use API key in header:

```bash
curl -H "Authorization: Bearer YOUR_KEY" \
  https://api.example.com/data
```

---

<!-- backgroundImage: url('https://images.unsplash.com/photo-1517694712202-14dd9538aa97?w=1200') -->
<!-- _color: white -->

# Core Features

- Fast performance
- Easy integration
- Secure by default

---

## Performance

### Time Complexity

Search operations: $O(log n)$

### Upload Formula

Optimal chunks equals file size divided by 4MB

---

## Error Codes

| Code | Meaning |
|------|---------|
| 200 | Success |
| 400 | Bad Request |
| 401 | Unauthorized |
| 404 | Not Found |

---

# Thank You

Questions? Contact: 23f2004319@ds.study.iitm.ac.in
