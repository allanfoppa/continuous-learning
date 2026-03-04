---
layout: home
title: Home
months:
  - name: january
    topic: OOP & Clean Code
  - name: february
    topic: Clean Architecture & Dependency Injection
  - name: march
    topic: Design Patterns
  - name: april
    topic: Testing & Quality Assurance with AI
  - name: may
    topic: Distributed Systems & Database Fundamentals
  - name: june
    topic: Backend Framework (NestJS) & Web APIs
  - name: july
    topic: AI Integration & MCP
  - name: august
    topic: CI/CD & DevOps
  - name: september
    topic: Monitoring
  - name: october
    topic: Frontend
  - name: november
    topic: Revision
  - name: december
    topic: 2027 Planning
---

Welcome to my structured learning path for 2026! This repository tracks my progress through backend development, software architecture, and best practices.

## 2026 Learning Path

### Monthly Focus Areas

{% for month in page.months -%}
- **[{{ month.name | capitalize }}]({{ "/2026/" | append: month.name | append: "/" | relative_url }})** - {{ month.topic }}
{% endfor %}

## About This Journey

This learning path is designed to build a solid foundation in the areas covered by my studies and to apply the knowledge gained during the "Payment Methods Workshop with a focus on Open Finance" at the Eldorado Research Institute.
