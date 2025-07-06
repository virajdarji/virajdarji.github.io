---
layout: post
title: "🚀 Launching My Data & AI Portfolio"
date: 2025-07-06 00:00:00 -0400
categories: announcements
---

Hey there — I’m **Viraj Darji**, a cloud‑native data engineer and ML enthusiast. After years of building data platforms for Fortune‑100 clients and experimenting with Generative AI, I’ve finally decided to put my work in one place.

---

## Why This Portfolio?

I wanted a **single hub** where recruiters, collaborators, and fellow tech‑nerds can:

1. **Explore real‑world projects** — from heart‑failure prediction pipelines on AWS + BigQuery to a LangChain‑powered NL‑to‑Viz assistant.
2. **Read deep‑dives** on topics I’m passionate about: data architecture, LLM Ops, Terraform best practices, and performance tuning.
3. **Follow my learning journey** as I experiment with new frameworks (looking at you, Iceberg ❄️) and share lessons learned.

---

## What to Expect

* **Project Walk‑throughs**: Step‑by‑step explanations of architecture, trade‑offs, and impact.
* **Code Snippets & Tutorials**: Hands‑on guides in Python, SQL, and Terraform.
* **Opinion Pieces**: My take on the evolving landscape of data engineering and AI.

> I believe in knowledge‑sharing and practical problem‑solving — this blog will focus on actionable insights you can apply immediately.

---

## Quick Preview: A Tasty BigQuery Optimization Trick

```sql
-- Reduce cost & runtime by filtering early using clustered columns
SELECT
  patient_id,
  predicted_risk
FROM
  `heart.failure_predictions`
WHERE
  _PARTITIONDATE BETWEEN '2025-07-01' AND '2025-07-05'
  AND predicted_risk > 0.8;
```

This simple partition prune cut our query cost by **70%** on a 50 M‑record table. Stay tuned for a full breakdown in an upcoming post.

---

## Connect with Me

* **Résumé**: [Download PDF](../assets/Viraj_Resume_DE_V1.pdf)
* **LinkedIn**: [linkedin.com/in/viraj-darji](https://linkedin.com/in/viraj-darji)
* **GitHub**: [github.com/virajdarji](https://github.com/virajdarji)

Thanks for stopping by — excited to share, learn, and grow together. 😊
