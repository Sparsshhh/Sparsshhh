<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,50:6a11cb,100:2575fc&height=220&section=header&text=Sparsh&fontSize=70&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Software%20Engineer%20%7C%20Backend%20%2B%20AI%2FML&descAlignY=55&descSize=18" width="100%"/>

<a href="https://github.com/Sparsshhh">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&duration=3000&pause=1000&color=A78BFA&center=true&vCenter=true&width=650&lines=Software+Engineer+%7C+Java+%2B+Spring+Boot;Applied+Machine+Learning+%2F+Computer+Vision;Backend+Systems+%2B+API+Security;Business+Intelligence+%26+Data+Analytics" alt="Typing SVG" />
</a>

<br/>

![CGPA](https://img.shields.io/badge/CGPA-9.29%2F10-6a11cb?style=for-the-badge&labelColor=1a1a2e)
![KIIT](https://img.shields.io/badge/KIIT-B.Tech%20CSE%20'26-2575fc?style=for-the-badge&labelColor=1a1a2e)
![Location](https://img.shields.io/badge/Patna,%20Bihar-India-8B5CF6?style=for-the-badge&labelColor=1a1a2e&logo=googlemaps&logoColor=white)

<br/>

<a href="https://linkedin.com/in/sparsshhh"><img src="https://img.shields.io/badge/LinkedIn-Connect-6a11cb?style=flat-square&logo=linkedin&logoColor=white&labelColor=1a1a2e"/></a>
<a href="mailto:sparsh3863@gmail.com"><img src="https://img.shields.io/badge/Email-Reach%20Out-7c3aed?style=flat-square&logo=gmail&logoColor=white&labelColor=1a1a2e"/></a>
<a href="https://github.com/Sparsshhh"><img src="https://img.shields.io/badge/GitHub-Sparsshhh-2575fc?style=flat-square&logo=github&logoColor=white&labelColor=1a1a2e"/></a>

<br/><br/>

![Profile Views](https://komarev.com/ghpvc/?username=Sparsshhh&color=6a11cb&style=flat-square&label=Profile+Views)
![Followers](https://img.shields.io/github/followers/Sparsshhh?style=flat-square&color=7c3aed&labelColor=1a1a2e)
![Stars](https://img.shields.io/github/stars/Sparsshhh?style=flat-square&color=2575fc&labelColor=1a1a2e)

</div>

---

## About Me

I'm a Computer Science undergraduate at **KIIT, Bhubaneswar** (CGPA 9.29), building software that has to hold up under real constraints — secure auth flows, real-time inference, and data pipelines that don't lie to the people reading the dashboard.

My work sits across three areas:

- **Backend Engineering** — designing secure, stateless REST APIs with Spring Boot, Spring Security, and JWT-based authentication and RBAC
- **Applied Machine Learning** — building and benchmarking computer vision models (CNNs) end-to-end, from data preprocessing to real-time inference
- **Business Intelligence** — modeling relational data into star-schemas and surfacing it through Power BI dashboards stakeholders actually use

I care less about "using a framework" and more about *why* a system is built the way it is — the caching strategy, the failure mode, the tradeoff. That mindset is what I bring to every project below.

```yaml
Open To:
  - Software Engineer (Backend / Full Stack) roles
  - Machine Learning Engineer roles
  - Internship-to-full-time or entry-level SDE positions
```

---

## Tech Stack

**Languages**

![Java](https://skillicons.dev/icons?i=java) ![Python](https://skillicons.dev/icons?i=python) ![JavaScript](https://skillicons.dev/icons?i=js) ![C](https://skillicons.dev/icons?i=c) ![SQL](https://skillicons.dev/icons?i=mysql)

**Frontend**

![HTML](https://skillicons.dev/icons?i=html) ![CSS](https://skillicons.dev/icons?i=css)

**Backend & Databases**

![Spring](https://skillicons.dev/icons?i=spring) ![MySQL](https://skillicons.dev/icons?i=mysql) ![MongoDB](https://skillicons.dev/icons?i=mongodb) ![Redis](https://skillicons.dev/icons?i=redis)

**AI / ML & Data Tools**

![TensorFlow](https://skillicons.dev/icons?i=tensorflow) ![OpenCV](https://skillicons.dev/icons?i=opencv) ![Jupyter](https://skillicons.dev/icons?i=jupyter)

**Tools & Platforms**

![Git](https://skillicons.dev/icons?i=git) ![GitHub](https://skillicons.dev/icons?i=github) ![VSCode](https://skillicons.dev/icons?i=vscode) ![Linux](https://skillicons.dev/icons?i=linux) ![Postman](https://skillicons.dev/icons?i=postman)

---

## AI / ML Expertise

| Domain | Proficiency | Details |
|---|:---:|---|
| Computer Vision (CNNs) | ⭐⭐⭐⭐☆ | Built and trained a CNN classifier for real-time image classification, benchmarked against a ResNet50 baseline |
| Model Evaluation | ⭐⭐⭐⭐☆ | Confusion matrix, precision, recall, and F1-score analysis for multi-class classification validation |
| Data Preprocessing | ⭐⭐⭐⭐☆ | ROI extraction, adaptive resizing, min-max normalization on custom image datasets (2,000+ samples) |
| Applied ML Frameworks | ⭐⭐⭐⭐☆ | TensorFlow, Keras, Scikit-learn |
| Classical ML Foundations | ⭐⭐⭐☆☆ | IBM Machine Learning Capstone (Coursera) — supervised/unsupervised learning fundamentals |

---

## Featured Projects

<details>
<summary><b>🔐 Journal & Sentiment Analysis Platform</b></summary>
<br/>

A secure, multi-user journal API with automated sentiment aggregation and third-party weather integration behind a resilient caching layer.

| | |
|---|---|
| **Stack** | Java, Spring Boot, Spring Security, MongoDB, Redis |
| **Scale** | Multi-user, role-based access across all endpoints |
| **Performance** | Redis-backed TTL caching to reduce redundant external API calls and response latency |
| **Security** | Stateless JWT authentication, Role-Based Access Control (RBAC), environment-separated dev/prod configs |
| **Impact** | Fully automated weekly analytics — from aggregation to email delivery — with zero manual intervention |
| **Repository** | [github.com/Sparsshhh/journal-sentiment-analysis-app](https://github.com/Sparsshhh/journal-sentiment-analysis-app) |

Designed and built end-to-end: Spring Security governs stateless JWT auth and RBAC, a cron-based scheduler uses MongoTemplate regex queries and the Java Stream API to aggregate weekly sentiment distributions, and a custom Redis serialization layer with TTL-based eviction insulates the system from third-party API rate limits. Jackson ObjectMapper standardizes JSON handling across asynchronous, multi-threaded scheduling workflows.

</details>

<details>
<summary><b>🤟 Real-Time ASL Hand Sign Recognition (CNN)</b></summary>
<br/>

A real-time computer vision system classifying 36 ASL hand signs via webcam, benchmarked against an industry-standard baseline.

| | |
|---|---|
| **Stack** | Python, TensorFlow, Keras, OpenCV |
| **Scale** | 36-class classification, 2,000+ curated and preprocessed images |
| **Performance** | ~94% real-time classification accuracy |
| **Security** | N/A — local inference pipeline |
| **Impact** | Validated against a ResNet50 baseline using confusion matrix, precision, recall, and F1-score |
| **Repository** | [github.com/Sparsshhh/asl-hand-sign-recognition](https://github.com/Sparsshhh/asl-hand-sign-recognition) |

Engineered a CNN architecture trained with the Adam optimizer and categorical cross-entropy loss to classify 36 ASL hand signs (A–Z, 0–9) in real time. Built a custom preprocessing pipeline — ROI extraction, adaptive resizing, min-max normalization — to improve generalization across a self-curated grayscale image dataset, then iteratively tuned hyperparameters under local hardware constraints.

</details>

<details>
<summary><b>📊 Sales Performance Dashboard</b></summary>
<br/>

A star-schema BI solution turning raw multi-relational sales data into stakeholder-ready KPI reporting.

| | |
|---|---|
| **Stack** | Power BI, Power Query, DAX, M Language |
| **Scale** | Multi-relational sales datasets modeled into a standardized star-schema |
| **Performance** | Reusable metric definitions across multiple report views |
| **Security** | N/A — internal BI reporting layer |
| **Impact** | Surfaced KPI trends, regional performance, and customer behavior patterns for business stakeholders |
| **Repository** | [github.com/Sparsshhh/sales-performance-dashboard](https://github.com/Sparsshhh/sales-performance-dashboard) |

Built ETL pipelines in Power Query to clean, transform, and model data into a star-schema optimized for analytical reporting. Authored custom DAX measures and M-language queries for gross profitability margins and rolling YoY growth, then structured the underlying data model for reuse across report views.

</details>

---

## Leadership & Co-Curricular

<table>
<tr>
<td width="70%">

**Esports Strategy Lead** — High-Tier T3 Esports Leagues
Led strategic gameplay execution and live-match tactical analysis in competitive team play, translating directly into structured problem-solving and decision-making under pressure.

`Strategic Thinking` `Team Leadership` `Real-Time Decision-Making`

</td>
</tr>
<tr>
<td width="70%">

**Public Speaking & Debate** — St. Karen's High School
Active participant in school debates and competitive sports, building communication and cross-functional teamwork skills.

`Communication` `Teamwork` `Public Speaking`

</td>
</tr>
</table>

---

## Achievements

<div align="center">

| Recognition | Details |
|---|---|
| Academic Excellence | CGPA 9.29/10 — B.Tech Computer Science, KIIT |
| Class XII (CBSE) | 95.2% |
| Class X (CBSE) | 94% |
| Model Performance | ~94% real-time accuracy on 36-class ASL sign recognition |

</div>

---

## Certifications

**IBM**

![IBM](https://img.shields.io/badge/Machine%20Learning%20Capstone-IBM%20%2F%20Coursera-6a11cb?style=for-the-badge&logo=ibm&logoColor=white&labelColor=1a1a2e)

**Microsoft**

![Microsoft](https://img.shields.io/badge/Power%20BI%20Desktop%20for%20BI-Microsoft%20%2F%20Udemy-2575fc?style=for-the-badge&logo=microsoft&logoColor=white&labelColor=1a1a2e)

**HackerRank**

![HackerRank](https://img.shields.io/badge/SQL%20(Advanced)-HackerRank-7c3aed?style=for-the-badge&logo=hackerrank&logoColor=white&labelColor=1a1a2e)

---

## GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Sparsshhh&show_icons=true&theme=tokyonight&hide_border=true&bg_color=1a1a2e&title_color=A78BFA&icon_color=8B5CF6&text_color=c9c9e8" width="49%"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=Sparsshhh&theme=tokyonight&hide_border=true&background=1a1a2e&ring=8B5CF6&fire=A78BFA&currStreakLabel=A78BFA" width="49%"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sparsshhh&layout=compact&theme=tokyonight&hide_border=true&bg_color=1a1a2e&title_color=A78BFA&text_color=c9c9e8" width="49%"/>

</div>

---

## GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=Sparsshhh&theme=algolia&no-frame=true&column=4&margin-w=10&margin-h=10&row=2"/>

</div>

---

## Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Sparsshhh&theme=react-dark&bg_color=1a1a2e&color=A78BFA&line=8B5CF6&point=ffffff&hide_border=true" width="95%"/>

</div>

---

## Contribution Snake

<div align="center">

<img src="https://raw.githubusercontent.com/Sparsshhh/Sparsshhh/output/github-contribution-grid-snake-dark.svg" width="95%"/>

</div>

> Requires the [`platane/snk`](https://github.com/Platane/snk) GitHub Action set up on this repo to generate the animation automatically.

---

## Current Focus

```yaml
Learning:
  - Advanced System Design
  - Distributed Caching Patterns
  - Deep Learning Architectures Beyond CNNs

Building:
  - Production-grade backend services with Spring Boot
  - End-to-end ML pipelines from data to deployment

Exploring:
  - LLM-based application development
  - Cloud-native deployment patterns

Open To:
  - Software Engineer / Backend Engineer roles
  - Machine Learning Engineer roles
  - Collaborating on open-source backend or ML projects
```

---

## Connect

<div align="center">

<a href="mailto:sparsh3863@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://linkedin.com/in/sparsshhh"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://github.com/Sparsshhh"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>

</div>

---

<div align="center">

*"Ship things that hold up when it matters."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2575fc,50:6a11cb,100:1a1a2e&height=120&section=footer"/>

</div>
