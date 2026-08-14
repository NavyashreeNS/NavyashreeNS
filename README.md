<div align="center">

# Navyashree N

### 🔬 Research Engineer — ML & GPU Systems

**I build systems for the operating room, where a millimetre is the tolerance and ten milliseconds is the whole budget.**

[![Portfolio](https://img.shields.io/badge/Portfolio-navyahtic.github.io-b4571f?style=for-the-badge&logo=firefox&logoColor=white)](https://navyahtic.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/navyashree-n-7bbab2280/)
[![Email](https://img.shields.io/badge/Email-Get_in_touch-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:navyashreensgr@gmail.com)

</div>

---

## 🧠 About

Project Associate at **IIT Madras' Healthcare Technology Innovation Centre**, building the GPU morphing stack for **imageless total knee arthroplasty** — reconstructing a patient's femur and tibia from points swept with a probe in theatre, instead of from a CT taken days earlier. The reconstruction has to land inside half a millimetre and finish inside a single surgical frame.

Most of what I've learned came from **replacing something that already worked**. The bone-synthesis pipeline I inherited ran on a thin-plate-spline formulation from 1989. It hit its landmarks and shrank the bone by two thirds. Rebuilding it around Bayesian Coherent Point Drift meant reading the 1989 paper closely enough to understand *why* it was written that way — then writing 89 tests, including one that checks the output is byte-identical run to run, because in a surgical pipeline reproducibility is a safety property rather than a nicety.

Before the research work I spent a year shipping applied ML — always taken past the notebook and served behind a real API, because a model nobody can call is a model nobody uses. **That habit is the throughline.** I like the part of the job where a result becomes a thing that runs.

- 🎓 **B.E. Computer Science**, VTU Bengaluru — CGPA 9+ / 10, Class of 2026
- 📍 Chennai & Bengaluru, India
- 🔭 Currently: GPU-accelerated surgical navigation at IITM HTIC
- 🌱 Open to software and ML engineering roles

---

## 🚀 Projects

<table>
<tr>
<td width="50%" valign="top">

### 🎓 [AI Tutor](https://github.com/NavyashreeNS/ai-tutor)
**A Socratic engine that will not give you the answer.**

Grounded in a knowledge dependency graph, so it knows exactly what it's withholding. When you get something wrong it works out *which* of 33 named misconceptions produced that answer, then asks the question designed to break it.

`18 concepts` · `28 edges` · `95 tests`

<sub>**TypeScript** · Next.js 15 · Bayesian Knowledge Tracing</sub>

</td>
<td width="50%" valign="top">

### 🌱 [EcoEcho](https://github.com/NavyashreeNS/ecoecho)
**Native planting from your actual conditions.**

Retrieval over a pgvector index rather than a lookup table keyed on a region name — then re-ranked against live weather at your coordinates, because similarity alone recommends a tree that needs 2000mm to someone with 450mm.

`16 species` · `384-dim` · `55 tests`

<sub>**Next.js 15** · Supabase · pgvector · Clerk</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🤖 [Applied ML Project Set](https://github.com/NavyashreeNS/applied-ml-project-set)
**Three models past the notebook, each served over HTTP.**

Spam classification at **99.5% accuracy**, car price regression cross-validated on 201 rows, and a housing model that scores R² 0.81 on a random split and **−0.13** on a geographically blocked one — the most useful result in the repo.

`39 tests` · Flask + FastAPI

<sub>**Python** · scikit-learn · pandas</sub>

</td>
<td width="50%" valign="top">

### ♿ [AI-RFID Navigation Assistant](https://github.com/NavyashreeNS/AI-RFID-Navigation-Assistant)
**Indoor wayfinding for visually impaired users.**

The radio isn't the hard part. A C++ layer debounces 215 raw reads into 8 arrivals, routing knows a staircase from a corridor, and the announcement policy decides when to *stay quiet*.

`80 Python tests` · `45 C++ checks`

<sub>**C++17** · Python · accessibility-aware Dijkstra</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔋 [EV Energy Recovery](https://github.com/NavyashreeNS/ev-efficiency-dc-generator)
**How much range does a 2.5 kW generator really recover?**

**22.5%** on an urban cycle — and modelling *why it isn't more* is the finding. Peak braking hits 32 kW against a 2.5 kW rating, so half of all braking time is spent above what the machine can absorb.

`84 tests` · full energy ledger

<sub>**Python** · NumPy · drive-cycle simulation</sub>

</td>
<td width="50%" valign="top">

### 🐾 [PetCare](https://github.com/NavyashreeNS/your_first_kid)
**Vaccination schedules that shift when a dose is late.**

A schedule is a series of *dependent intervals*, not a list of dates. Counting doses isn't enough either — three doses finished at 14 weeks is not protection, and the app says so.

`66 tests` · zero dependencies

<sub>**Vanilla JS** · no build step · offline-first</sub>

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**GPU & Systems**

![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Holoscan](https://img.shields.io/badge/Holoscan_SDK-76B900?style=flat-square&logo=nvidia&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)

**Machine Learning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

**Backend & Data**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**Web & Cloud**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)

</div>

---

## 💼 Experience

**Project Associate** · *IITM HTIC MedTech Incubator, IIT Madras* · Chennai · Jun 2026 – Present
> GPU morphing stack for imageless total knee arthroplasty navigation — neural signed distance fields, Gaussian RBF field-space warping, and a Holoscan operator graph that closes the loop inside a single surgical frame. Moved bone synthesis off a 1989 thin-plate-spline formulation onto Bayesian Coherent Point Drift, shipped as drop-in executables so the surgical software adopted it without a single call-site change.

**Project Intern** · *IITM HTIC, IIT Madras* · Feb 2026 – Jun 2026
> Prototyped and benchmarked the real-time bone morphing algorithms behind the team's MICCAI 2026 workshop submission.

**Data Science Intern** · *Oasis Infobyte* · Mar 2025 – Jul 2025
> Three end-to-end ML projects, each taken past the notebook and served behind a REST API. Reproducibility as the deliverable.

---

## 🏆 Highlights

- 🥈 **Runner-Up, Paper Presentation** — ICRCCT 2K24, for temporal graph neural network work on predictive maintenance
- 🎖️ **Young Turks 2025** — 96.32nd percentile, India's largest campus skill contest
- 🌟 **Aspire Leaders Program 2025** — selected cohort, Aspire Institute (founded by Harvard Business School faculty)
- 📜 **Oracle Certified Generative AI Professional** · **UiPath Automation Developer Associate** · **AWS Academy Cloud Foundations & Cloud Security**
- 👩‍💻 Google Developer Group member · SHEfi Scholar · GSSoC open-source contributor

---

<div align="center">

### 📊 GitHub

![Stats](https://github-readme-stats.vercel.app/api?username=NavyashreeNS&show_icons=true&hide_border=true&count_private=true&title_color=b4571f&icon_color=b4571f&hide=issues)
![Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=NavyashreeNS&layout=compact&hide_border=true&title_color=b4571f&langs_count=8)

---

**Currently open to software and ML engineering roles.**

[![Portfolio](https://img.shields.io/badge/See_the_full_portfolio-navyahtic.github.io-b4571f?style=for-the-badge)](https://navyahtic.github.io)

</div>
