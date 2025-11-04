# DevOps Pages Lab

DevOps Assignment: Publish with GitHub Pages + Auto Activity Log

## 🧭 Recent Activity
<!--START_SECTION:activity-->
<!--END_SECTION:activity-->

---

## 🕒 Scheduling Rationale
This workflow runs **every 12 hours** using a cron schedule (`0 */12 * * *`).  
The interval balances **freshness and API efficiency**, keeping the activity list up to date  
without exceeding GitHub’s rate limits.  
It can also be manually triggered from the **Actions** tab for on-demand updates.

---

## 💡 Reflection
Through this assignment, I learned how **CI/CD pipelines** can extend beyond code deployment —  
they can automate content updates and publishing as well.  

In this project:
- GitHub Actions validates and transforms activity data from the API.  
- Markdown serves as both documentation and a publishable artifact via **GitHub Pages**.  
- Using `index.md` with `include_relative` allows Pages to render a live, auto-updated site.  

This demonstrates how DevOps principles — automation, traceability, and reproducibility —  
apply not just to software builds but also to content workflows.

---

## 📘 Project Info
- **Owner:** 93weiwei  
- **Course:** DevOps
