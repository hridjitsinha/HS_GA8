---
marp: true
theme: default
paginate: true
footer: '23f2004319@ds.study.iitm.ac.in'
style: |
  section {
    background-color: #ffffff;
    color: #2d2d2d;
    padding: 30px;
  }
  h1, h2, h3 {
    color: #0055aa;
    font-weight: 700;
  }
  code {
    font-size: 0.9em;
  }
---

# API Documentation  
A straightforward guide to understanding and using our REST API.

**Contact**: 23f2004319@ds.study.iitm.ac.in

---

## Getting Started

This guide walks through the essentials of our API with simple, clear examples so you can plug in and build quickly.

---

## Authentication

Send your API key in the request header:

```bash
curl -H "Authorization: Bearer YOUR_KEY" \
     https://api.example.com/data
