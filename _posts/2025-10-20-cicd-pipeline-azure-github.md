---
layout: post
title: "Building My First CI/CD Pipeline with GitHub & Azure Static Web Apps"
date: 2025-10-20
description: "How I built an automated CI/CD workflow that deploys every commit to Azure."
tags: [CI/CD, DevOps, GitHub Actions, Azure, Automation]
---

🚀 **Today I completed my first CI/CD pipeline** — and it’s fully automated!

This project links **GitHub Actions** with **Azure Static Web Apps** so every push to `main` automatically builds and deploys the new version.

---

## 🧱 Step 1: Project Setup

I started with a minimal static site:

```html
<h1>🚀 CI/CD Demo: Azure Static Web App</h1>
<p>This site automatically redeploys on every push to <code>main</code>.</p>
<footer><small><!-- COMMIT_SHA --></small></footer>
