---
layout: post
title: "🏥 Real-Time Heart Failure Prediction with BigQuery and Vertex AI"
date: 2025-07-06 00:00:00 -0400
categories: machine-learning healthcare
---

In this post, I’ll walk you through how we built a real-time heart failure prediction platform for HCA Healthcare, handling over **50 million records** with **BigQuery**, **Vertex AI**, and **Cloud Composer**.

### ⚙️ Tech Stack
- Google Cloud Platform (BigQuery, Vertex AI, Cloud Composer)
- Python, SQL
- Real-time API integration

### 📌 Highlights
- Built ML-ready feature pipelines to transform structured + unstructured patient data
- Used Vertex AI to deploy trained models for real-time predictions
- Logged predictions in BigQuery for traceability and compliance
- Reduced ETL latency by 40% using optimized DAGs in Cloud Composer

This system helped doctors reduce manual assessment time by 60% and impacted 5–8% of high-risk patients.

➡️ In the next post, I’ll dive into our feature engineering strategies and how we optimized them using BigQuery SQL functions.

<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-SKGL727DK0"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-SKGL727DK0');
</script>
