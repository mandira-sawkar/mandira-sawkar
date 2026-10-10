<!-- ===================== HEADER ===================== -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:{{PRIMARY_HEX}},100:{{SECONDARY_HEX}}&height=220&section=header&text=Mandira%20Sawkar&fontSize=52&fontColor=ffffff&fontAlignY=36&desc=Research%20Engineer%20%C2%B7%202x%20EMNLP%20First%20Author&descAlignY=58&descSize=18&animation=fadeIn" width="100%" alt="Mandira Sawkar banner"/>
</p>

<p align="center">
  <a href="https://mandira-sawkar.github.io/">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3000&pause=900&color={{ACCENT_HEX}}&center=true&vCenter=true&width=640&lines=LLM+Evaluation+%26+LLM-as-a-Judge;Responsible+%26+Socially+Aligned+NLP;Production+ML+Pipelines+at+Scale;Turning+messy+text+into+measurable+evidence" alt="Typing tagline"/>
  </a>
</p>

<p align="center">
  <a href="https://mandira-sawkar.github.io/"><img src="https://img.shields.io/badge/Portfolio-{{ACCENT_HEX}}?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio"/></a>
  <a href="https://mandira-sawkar.github.io/cv/"><img src="https://img.shields.io/badge/CV-{{SECONDARY_HEX}}?style=for-the-badge&logo=readthedocs&logoColor=white" alt="CV"/></a>
  <a href="https://scholar.google.com/citations?hl=en&user=lbaywYoAAAAJ"><img src="https://img.shields.io/badge/Google%20Scholar-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white" alt="Google Scholar"/></a>
  <a href="https://www.linkedin.com/in/mandira-sawkar"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:mandirasawkar@gmail.com"><img src="https://img.shields.io/badge/Email-{{PRIMARY_HEX}}?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

<p align="center">📍 Sunnyvale, CA &nbsp;·&nbsp; 🎓 M.S. Artificial Intelligence, RIT &nbsp;·&nbsp; 🔎 Open to ML / NLP / Research Engineer roles</p>

---

## 👋 About Me

I'm a research engineer working where **responsible NLP** meets **production engineering**.
I build LLM-as-a-judge pipelines, validate them against human experts, and ship ML systems that hold up on real, large-scale data.

Before research, I spent 4+ years building ML and automation systems in industry. That's why I care about evaluation that is rigorous, reproducible, and actually usable.

> **Currently interested in:** LLM evals · AI safety · socially aligned NLP · large-scale data systems

---

## ⚡ Selected Impact

<table>
  <tr>
    <td align="center" width="33%">
      <h3>6.7M</h3>
      parliamentary speeches analyzed with an LLM-as-a-judge pipeline
    </td>
    <td align="center" width="33%">
      <h3>κ = 0.711</h3>
      LLM agreement with human consensus<br/><sub>(human–human κ = 0.644)</sub>
    </td>
    <td align="center" width="33%">
      <h3>3 hrs → 20 min</h3>
      per-batch analysis runtime in a production ML pipeline
    </td>
  </tr>
</table>

---

## 📄 Publications

| | Paper | Venue | Role | Links |
|:-:|---|---|---|---|
| 🏛️ | **Two Centuries of Sexism in British Parliament:** A Computational Analysis of Women's Representation in the Hansard Corpus | EMNLP 2026 · Main | Co-first author | [Paper]({{EMNLP_2026_PAPER_URL}}) · [arXiv]({{ARXIV_URL}}) · [Code](https://github.com/mandira-sawkar/Two-Centuries-of-Sexism) |
| 🧩 | **LPI-RIT at LeWiDi-2025:** Improving Distributional Predictions via Metadata and Loss Reweighting with DisCo | NLPerspectives Workshop · EMNLP 2025 | Co-first author | [Paper](https://aclanthology.org/2025.nlperspectives-1.17/) · [Code](https://github.com/mandira-sawkar/LeWiDi3_NLPeerespectives_2025) |

<sub>📚 Full list on <a href="https://scholar.google.com/citations?hl=en&user=lbaywYoAAAAJ">Google Scholar</a></sub>

---

## 🔬 Featured Work

<table>
  <tr>
    <td width="50%" valign="top">
      <img src="{{hansard_thumbnail}}" width="100%" alt="Hansard project preview"/>
      <h3>🏛️ Hansard Sexism Analysis</h3>
      <b>Problem:</b> Measure sexist rhetoric across 200 years of UK parliamentary debate.<br/>
      <b>Built:</b> Psychology-grounded taxonomy, 300-speech human validation set, cross-model LLM judging.<br/>
      <b>Result:</b> Sexism in 54% of anti-suffrage vs. 21% of pro-suffrage speeches.<br/><br/>
      <a href="https://github.com/omarkhursheed/hansard-nlp-explorer"><img src="https://img.shields.io/badge/Code-181717?style=flat-square&logo=github" alt="Code"/></a>
      <a href="{{EMNLP_2026_PAPER_URL}}"><img src="https://img.shields.io/badge/Paper-{{ACCENT_HEX}}?style=flat-square&logo=arxiv&logoColor=white" alt="Paper"/></a>
    </td>
    <td width="50%" valign="top">
      <img src="{{lewidi_thumbnail.png}}" width="100%" alt="LeWiDi project preview"/>
      <h3>🧩 Disagreement-Aware Modeling</h3>
      <b>Problem:</b> Single labels erase minority perspectives in subjective tasks.<br/>
      <b>Built:</b> Extended DisCo with annotator-metadata embeddings and task-aligned losses.<br/>
      <b>Result:</b> ~40% lower soft-label distance on CSC and Paraphrase.<br/><br/>
      <a href="https://github.com/Homan-Lab/lewidi3_public"><img src="https://img.shields.io/badge/Code-181717?style=flat-square&logo=github" alt="Code"/></a>
      <a href="https://aclanthology.org/2025.nlperspectives-1.17/"><img src="https://img.shields.io/badge/Paper-{{ACCENT_HEX}}?style=flat-square&logo=bookstack&logoColor=white" alt="Paper"/></a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>⚖️ LLM-as-a-SupremeCourt-Judge</h3>
      Evaluated 200+ U.S. Supreme Court cases to measure how panel size, prompting strategy, and ideology personas shift LLM–judge alignment.<br/><br/>
      <a href="https://github.com/mandira-sawkar/LLM-as-a-SupremeCourt-Judge"><img src="https://img.shields.io/badge/Code-181717?style=flat-square&logo=github" alt="Code"/></a>
    </td>
    <td width="50%" valign="top">
      <h3>🕵️ Detecting Deception</h3>
      Logic-gated fact-checking with DistilRoBERTa and contradiction detection. Validated on 7,200+ claims at 83% accuracy, with selective overrides for low-confidence predictions.<br/><br/>
      <a href="https://github.com/mandira-sawkar/Intelligent-Systems-for-Fighting-Misinformation"><img src="https://img.shields.io/badge/Code-181717?style=flat-square&logo=github" alt="Code"/></a>
    </td>
  </tr>
</table>

<details>
<summary><b>🗂️ More projects</b></summary>
<br/>

| Project | What it does | Highlight |
|---|---|---|
| [Two Centuries of Sexism](https://github.com/mandira-sawkar/Two-Centuries-of-Sexism) | LLM-as-a-Judge framework featuring 1.2 million historic parliamentary debates| LLM Evals |
| [Learning With Disagreements](https://github.com/mandira-sawkar/LeWiDi3_NLPerspectives_2025) | Modelling annotators and non-binary labels | Multilayer Perceptron, NLI |
| [LLM-as-a-SupremeCourt-Judge](https://github.com/mandira-sawkar/LLM-as-a-SupremeCourt-Judge) | LLM-as-a-Judge framework evaluating 200 Supreme Court cases | LLM Classification |
| [Detecting Deception](https://github.com/mandira-sawkar/ Intelligent-Systems-for-Fighting-Misinformation) | Fake news detection with DistilRoBERTa with logic-gated ML overrides | RoBERTa + Logic gates |

</details>

---

## 💼 Experience

```mermaid
timeline
    title Career Path
    2020 - 2023 : Software Engineer · WSP Global
    2023 - 2024 : ML Engineer · Kloud9
    2024 - 2026 : M.S. Artificial Intelligence · RIT
    2025 - 2026 : 2x EMNLP co-first-author papers
```

<details>
<summary><b>🧠 Machine Learning Engineer — Kloud9</b> &nbsp;·&nbsp; Apr 2023 – Jul 2024</summary>
<br/>

- Built a ghost-inventory prediction pipeline across 50+ features and multimillion-row datasets: **92% accuracy**, **10% fewer stock discrepancies**.
- Cut per-batch analysis runtime from **3 hours to 20 minutes**.
- Reduced production deployment time by **~80%** with data-engineering and business teams.
- Mentored **5+ interns** in feature engineering, PySpark, and ML evaluation, leading to **3 full-time hires**.

</details>

<details>
<summary><b>⚙️ Software Engineer — WSP Global</b> &nbsp;·&nbsp; Oct 2020 – Apr 2023</summary>
<br/>

- Built a CLI tool automating onboarding for **60,000+ employees annually**, saving **2.5 human-months per year**.
- Cut operations overhead by **71%** with an automated project-archival pipeline.
- Validated **80,000+ employee records monthly** with a Python and Pandas data-quality system.

</details>

<details>
<summary><b>🎓 Education</b></summary>
<br/>

- **M.S. Artificial Intelligence** — Rochester Institute of Technology, May 2026 · GPA 3.7
  Thesis: *Two Centuries of Sexism in British Parliament* · Advisor: Dr. Ashiqur R. KhudaBukhsh
- **PG Certification, Software Engineering for Data Science** — IIIT Hyderabad, 2023 · Distinction
- **Bachelor of Computer Applications** — IGNOU, 2020 · First Class

</details>

---

## 🛠️ Toolkit

**Languages**
<p>
  <img src="https://skillicons.dev/icons?i=python,cpp,c,java,r,powershell&theme={{ICON_THEME}}" alt="Languages"/>
</p>

**ML · NLP · LLMs**
<p>
  <img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn&theme={{ICON_THEME}}" alt="ML frameworks"/>
  <br/>
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face"/>
  <img src="https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white" alt="MLflow"/>
  <img src="https://img.shields.io/badge/Weights%20%26%20Biases-FFBE00?style=flat-square&logo=weightsandbiases&logoColor=black" alt="W&B"/>
  <img src="https://img.shields.io/badge/LLM--as--a--Judge-{{ACCENT_HEX}}?style=flat-square" alt="LLM-as-a-Judge"/>
  <img src="https://img.shields.io/badge/RAG-{{ACCENT_HEX}}?style=flat-square" alt="RAG"/>
</p>

**Data · Cloud · Deployment**
<p>
  <img src="https://skillicons.dev/icons?i=aws,gcp,azure,docker,flask,git&theme={{ICON_THEME}}" alt="Cloud and deployment"/>
  <br/>
  <img src="https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white" alt="Spark"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy"/>
  <img src="https://img.shields.io/badge/Dask-FDA061?style=flat-square&logo=dask&logoColor=black" alt="Dask"/>
  <img src="https://img.shields.io/badge/SQL-{{SECONDARY_HEX}}?style=flat-square&logo=postgresql&logoColor=white" alt="SQL"/>
</p>

---

## 🏆 Recognition

- 🥇 **1st place of ~60 presentations** — RIT Graduate Showcase 2025, *AI Alignment in Criminal Justice*
- 🖼️ **Poster** — RIT Graduate Showcase 2025, *LLM-as-a-SupremeCourt-Judge*

---

## 🤝 Let's Connect

I'm happy to talk about LLM evaluation, AI safety, responsible NLP, or research engineering roles.

<p align="center">
  <a href="mailto:mandirasawkar@gmail.com">📧 Email</a> &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/mandira-sawkar">💼 LinkedIn</a> &nbsp;·&nbsp;
  <a href="https://mandira-sawkar.github.io/">🌐 Portfolio</a> &nbsp;·&nbsp;
  <a href="https://scholar.google.com/citations?hl=en&user=lbaywYoAAAAJ">📚 Scholar</a>
</p>

<!-- ===================== FOOTER ===================== -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:{{SECONDARY_HEX}},100:{{PRIMARY_HEX}}&height=120&section=footer" width="100%" alt="Footer wave"/>
</p>