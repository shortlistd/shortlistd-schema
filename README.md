# shortlistd.io — Structured Data & Schema Markup

This repository contains the **official JSON-LD schema markup** used across https://www.shortlistd.io.

The schemas here are designed to help search engines and AI systems accurately understand:
- What shortlistd.io does
- How the product works
- Who it is for
- How it should appear in rich search results

This repository is the **single source of truth** for structured data related to shortlistd.io.

---

## 🧠 What shortlistd.io Is

shortlistd.io is an **autonomous AI recruitment platform** that uses AI agents to:
- Source candidates using semantic search
- Conduct structured, AI-led voice interviews
- Deliver decision-ready shortlists

It replaces manual recruitment work such as CV screening, keyword filtering, and first-round interviews.

---

## 📦 Schema Coverage

This repository includes validated JSON-LD schemas for:

### Core Pages
- Homepage
- Features
- Pricing
- About
- Blog
- Contact

### Schema Types Implemented
- `SoftwareApplication`
- `Service`
- `Organization`
- `Founders`
- `Article`
- `BlogPosting`
- `BreadcrumbList`
- `FAQPage`
- `ContactPage`
- `LocalBusiness`
- `VideoObject`

All schemas validate successfully using Google Rich Results Test.

---

## 🎯 Rich Results Eligibility

The structured data enables eligibility for:
- Software / Product rich snippets
- FAQ expandables
- Blog article carousels
- Breadcrumb navigation
- Knowledge Graph signals
- Contact cards
- Video results
- Review stars (where applicable)

---

## 🛠 Implementation Notes

- Schemas are injected via CDN-hosted JSON files
- Loaded dynamically in Framer
- Cache-busted on updates
- No inline HTML JSON-LD duplication

This approach keeps markup maintainable and scalable.

---

## 🔍 Validation Status

- ✅ All pages validated
- ✅ 0 critical errors
- ✅ 15+ rich result types eligible
- ✅ Fully compliant with Google structured data guidelines

---

## 🔗 Related Resources

- Website: https://www.shortlistd.io
- Features: https://www.shortlistd.io/features
- Pricing: https://www.shortlistd.io/pricing
- Blog: https://www.shortlistd.io/blog
- Contact: https://www.shortlistd.io/contact

---

## 📄 License & Usage

This structured data is provided to help search engines and AI systems accurately represent shortlistd.io.

For verification or updates, refer to the official website.

© 2023–2025 Shortlistd, Inc. All rights reserved.
