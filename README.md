<div align="center">

<!-- Animated SVG Header -->
<svg width="800" height="120" viewBox="0 0 800 120" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <style>
      .title { font: 500 32px 'Segoe UI', sans-serif; fill: #0f172a; }
      .sub { font: 400 15px 'Segoe UI', sans-serif; fill: #475569; }
      .tag { font: 400 13px 'Segoe UI', sans-serif; }
      .slide { animation: slideIn 0.8s ease forwards; opacity: 0; }
      .slide2 { animation: slideIn 0.8s 0.3s ease forwards; opacity: 0; }
      .slide3 { animation: slideIn 0.8s 0.6s ease forwards; opacity: 0; }
      @keyframes slideIn { from { opacity:0; transform: translateY(12px); } to { opacity:1; transform: translateY(0); } }
    </style>
  </defs>
  <text x="400" y="46" text-anchor="middle" class="title slide">Santosh Pujeri</text>
  <text x="400" y="74" text-anchor="middle" class="sub slide2">Senior Backend Engineer · Java · Spring Boot · Distributed Systems · Fintech</text>
  <text x="400" y="100" text-anchor="middle" class="sub slide3">📍 Bengaluru, India &nbsp;·&nbsp; 6+ years experience &nbsp;·&nbsp; Open to opportunities</text>
</svg>

<!-- Typing SVG -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&duration=3000&pause=1000&color=185FA5&center=true&vCenter=true&multiline=false&width=600&lines=Backend+Engineer+%7C+Java+%7C+Spring+Boot;Distributed+Systems+%7C+Redis+%7C+Microservices;Building+APIs+that+handle+50K%2B+events%2Fday;Idempotency+%7C+Concurrency+%7C+System+Design)](https://git.io/typing-svg)

<!-- Social Badges -->
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/santosh-pujeri)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:16santoshpujari@gmail.com)
[![LayoffFund](https://img.shields.io/badge/LayoffFund.com-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://layofffund.com)
[![Profile Views](https://komarev.com/ghpvc/?username=pujerisantosh&style=for-the-badge&color=185FA5&label=PROFILE+VIEWS)](https://github.com/pujerisantosh)

</div>

---

## 🚀 About Me

```java
public class SantoshPujeri extends BackendEngineer {

    String location     = "Bengaluru, India";
    int    experience   = 6; // years
    String currentRole  = "Senior Backend Engineer @ Appvestor";
    
    String[] expertise  = { "Distributed Systems", "Microservices", 
                             "System Design (HLD/LLD)", "Idempotency",
                             "High-Concurrency APIs", "Fintech Platforms" };
    
    String[] learning   = { "Advanced Distributed Systems", "Kafka", "gRPC" };
    
    boolean openToWork  = true; // Senior Backend / System Design roles
    
    String superpower() {
        return "Eliminating race conditions before they reach production 🔒";
    }
}
```

---

## 🛠️ Tech Stack

**Languages**

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Frameworks & APIs**

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Spring Cloud](https://img.shields.io/badge/Spring_Cloud-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![REST API](https://img.shields.io/badge/REST_APIs-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

**Databases & Cache**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

**Cloud & DevOps**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/CI%2FCD-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

**Testing**

![JUnit](https://img.shields.io/badge/JUnit5-25A162?style=for-the-badge&logo=junit5&logoColor=white)
![Mockito](https://img.shields.io/badge/Mockito-78C257?style=for-the-badge&logo=java&logoColor=white)

---

## 📈 Impact at a Glance

<div align="center">

| Metric | Achievement |
|--------|------------|
| ⚡ API Latency | Reduced p99 by **~60%** via query optimization & index redesign |
| 🔒 Race Conditions | **Zero incidents** post Redis distributed locking implementation |
| 🚀 CI/CD | Cut release cycle by **40%** at Appvestor |
| 🤖 QA Automation | Eliminated **~12 hrs/week** of manual testing at Synechron |
| 💾 DB Load | Reduced by **~60%** with Redis TTL caching strategies |
| 📊 Data Scale | Built pipelines serving **5M+ student records** |

</div>

---

## 💼 Experience

<details>
<summary><b>🔴 Senior Backend Engineer — Appvestor, Bengaluru (Jul 2024 – Present)</b></summary>
<br>

- Designed high-concurrency REST APIs for a mobile growth & analytics platform processing **50K+ events/day**; built idempotent service-layer logic with concurrency-safe validations that **eliminated payment inconsistency errors** in production.
- Drove architectural decision to use **Redis distributed locking** over DB-level locks for concurrent payment workflows — zero race-condition incidents post-deployment.
- Optimised PostgreSQL/MySQL query execution plans by analysing slow-query logs and redesigning indexes; reduced critical API **p99 latency by ~60%** and cut **CI/CD release cycle by 40%**.

</details>

<details>
<summary><b>🟠 Software Engineer — Synechron, Bengaluru (May 2021 – Jul 2024)</b></summary>
<br>

- Built and owned Java/Spring Boot microservices in a large-scale **financial platform handling 100K+ daily transactions**; drove API design, data-layer architecture, and service integration across 5+ distributed teams.
- Proposed and drove adoption of **automated JUnit/Mockito regression pipelines** — eliminated ~12 hrs/week of manual QA effort and enabled same-day releases on AWS CI/CD infrastructure.
- Designed **Redis caching strategies** on high-read financial endpoints — TTL-based invalidation reduced DB load by ~60%; resolved N+1 query patterns improving batch throughput by ~45%.

</details>

<details>
<summary><b>🟡 IT Analyst — Vedantu & BYJU'S, Bengaluru (Jul 2018 – Jun 2021)</b></summary>
<br>

- Built data validation and extraction pipelines serving **5M+ student records**; automated workflows using SQL and internal APIs, improving dataset accuracy by ~30%.
- Standardised validation logic and data contracts across teams — reduced data discrepancy incidents by **40% quarter-on-quarter**.

</details>

---

## 🌟 Featured Projects

### 🏦 [LayoffFund](https://layofffund.com) — Production Crowdfunding Platform
> `Java` `Spring Boot 3.2` `PostgreSQL` `JWT` `Razorpay` `AWS S3` `Docker` `Cloudflare CDN`

- Architected end-to-end platform with **JWT-secured REST APIs** and idempotent Razorpay payment processing
- **Zero duplicate charge incidents** since launch
- Adapter Pattern enables **zero-touch Stripe migration** with no business-logic changes

---

### 🎟️ [BookMyShow Clone](https://github.com/pujerisantosh/BooKMyShowProject2025) — Distributed Ticket Booking
> `Java` `Spring Boot` `MySQL` `Redis SETNX Distributed Locking`

- Solved **concurrent double-booking at scale** using Redis SETNX + TTL
- Load tested at **500 concurrent seat-reservation requests** with zero conflicts

---

### 💳 Payment Service — Idempotent Webhook Backend
> `Spring Boot` `PostgreSQL` `Docker` `JUnit` `Mockito` `HMAC Webhook Verification`

- Idempotent APIs with **state-machine transaction handling** and HMAC-verified Stripe webhooks
- **Replay-attack protection** · **100% JUnit/Mockito coverage** · Fully Dockerised

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=pujerisantosh&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" width="48%" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=pujerisantosh&theme=tokyonight&hide_border=true" width="48%" />
</div>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=pujerisantosh&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" width="40%" />
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=pujerisantosh&theme=tokyo-night&hide_border=true&area=true" width="95%" />
</div>

---

## 🏆 Achievements

<div align="center">

[![trophy](https://github-profile-trophy.vercel.app/?username=pujerisantosh&theme=tokyonight&no-frame=true&row=1&column=6)](https://github.com/ryo-ma/github-profile-trophy)

</div>

---

## 🎓 Education

| Degree | Institution | Year |
|--------|------------|------|
| 🎓 M.S. Computer Software Engineering | Scaler Academy | 2024–2025 |
| 🎓 B.E. Electrical, Electronics & Communications | Visvesvaraya Technological University | 2014–2018 |

**Scaler coursework:** DSA · SQL · LLD · HLD · Distributed Systems · Advanced Backend Engineering

---

## 📫 Let's Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/santosh-pujeri)
&nbsp;
[![Email](https://img.shields.io/badge/Send_an_Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:16santoshpujari@gmail.com)

<br>

![Snake animation](https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg)

<br>

*💡 Open to Senior Backend Engineer / System Design roles in Bengaluru or Remote*

</div>
