---
layout: post
title: "Building My First CI/CD Pipeline with GitHub & Azure Static Web Apps"
date: 2025-10-20
description: "Step-by-step how I built a fully automated CI/CD pipeline that deploys every commit to Azure."
tags: [CI/CD, DevOps, GitHub Actions, Azure, Automation]
---

🚀 **Today I finished building my first full CI/CD pipeline** — and it works like magic.

This project connects **GitHub Actions** with **Azure Static Web Apps**, so every time I push a change to the `main` branch, the website automatically rebuilds and redeploys. No manual uploads. No FTP. Just code → commit → live.

---

## 🧱 Step 1: Project Setup

I created a simple `index.html` file to serve as the static site.

```html
<h1>🚀 CI/CD Demo: Azure Static Web App</h1>
<p>This site automatically redeploys on every push to <code>main</code>.</p>
<footer><small><!-- COMMIT_SHA --></small></footer>
