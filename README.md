<p align="center">
  <img src="https://raw.githubusercontent.com/RonKat2008/RonKat2008/main/orbit.svg" alt="Ronit Katikaneni — Electrical Engineering and Computer Sciences at UC Berkeley" width="100%">
</p>

<p align="center">
  <a href="https://ronitkatikaneni.vercel.app"><b>Portfolio</b></a> ·
  <a href="https://ieeexplore.ieee.org/document/11315089"><b>IEEE RTSS 2025 paper</b></a> ·
  <a href="https://github.com/RonKat2008/Mantis-Prime-Agent"><b>PR review agent</b></a> ·
  <a href="https://github.com/RonKat2008/kidneyplate"><b>KidneyPlate</b></a> ·
  <a href="mailto:ronitkat08@berkeley.edu"><b>Email</b></a> ·
  <a href="https://www.linkedin.com/in/ronit-katikaneni-80a3b127b/"><b>LinkedIn</b></a>
</p>

---

I'm an Electrical Engineering &amp; Computer Sciences student at UC Berkeley, B.S. expected May 2030,
from Cypress, Texas. I build machine-learning systems and the tooling around them: agent
infrastructure at Mantis AI, a published real-time-systems paper, and a nutrition app for people
managing chronic kidney disease.

<br>

<table>
<tr><td width="50%" valign="top">

### 🛰️ [Prime Agent](https://github.com/RonKat2008/Mantis-Prime-Agent)

A pull-request reviewer that gathers its evidence with plain code before any model runs: AST diffs,
call-site discovery, git history, CI status. Three models from three labs then judge that evidence
and post line-anchored comments with committable fixes.

It also mines git history into a co-change graph of **2,700+ edges**, so it can flag a pull request
that touches a file without the files that usually change alongside it. Layered safety gates —
dry-run, rate caps, duplicate prevention — and **809 tests at 96% coverage**.

`Python` · `PRIME harness` · `GitHub API`

</td><td width="50%" valign="top">

### 🩺 [KidneyPlate](https://github.com/RonKat2008/kidneyplate) · [API](https://github.com/RonKat2008/KidneyPlateFastAPI)

Nutrition tracking across **1,000+ foods** for people managing chronic kidney disease, who have to
watch nutrients most food labels bury.

A chatbot answers dietary questions from a kidney-nutrition knowledge base I built, using
retrieval-augmented generation, so the advice is grounded rather than generic.

`React Native` · `TypeScript` · `FastAPI` · `Firebase` · `Supabase pgvector`

</td></tr>
<tr><td width="50%" valign="top">

### 📄 [IDK Cascades × Random Forest](https://ieeexplore.ieee.org/document/11315089)

**IEEE Real-Time Systems Symposium 2025**, work-in-progress track, with Albert M. K. Cheng and
Thomas Carroll at the University of Houston.

An IDK Cascade chains classifiers of increasing cost, each free to answer "I don't know" and defer
to the next. Replacing its fixed skip thresholds with a Random Forest cut **30–300 ms** from cascade
runtime on hard inputs, where fixed thresholds waste the most time.

`Python` · `scikit-learn`

</td><td width="50%" valign="top">

### 🔬 [Comet Former](https://github.com/RonKat2008/CometFormer)

A segmentation model for comet assay images — a lab test for DNA damage, where fragmented DNA
trails behind a cell like a comet's tail.

Built on U-MixFormer inside the MMSegmentation framework, then tuned with data augmentation and
hyperparameter search for generalization.
[Write-up](https://www.researchgate.net/publication/391512211).

`Python` · `PyTorch` · `MMSegmentation`

</td></tr>
</table>

<br>

### Now

**Software Engineer, Mantis AI** — May 2026 to present

- Rebuilt the finance chart panel in TypeScript around candlesticks, so real-time data reads at a glance.
- Automated finance-space creation in Python by wiring the Mantis SDK to the AlphaVantage market-data API.
- Building a Python capability framework that hands an agent domain-specific tools based on what the user asks for.

**Before that** — Full-stack intern at the Child Poverty Action Lab through Code2College, where I
built geolocation and a coordinate-based neighborhood search across 20+ regions for a door-to-door
canvassing tool, in React and Mapbox GL. One of 8 interns out of 20 chosen to present to leadership.

<br>

### Tools

```text
Languages    Python · TypeScript · Java · C++
Web          React · React Native · FastAPI · Flask · Astro
ML           PyTorch · scikit-learn · MMSegmentation · OpenCV
Infra        Docker · Firebase · Supabase · Mapbox · Git
```

Certification: Machine Learning Specialization, DeepLearning.AI

<br>

### Outside the code

President of my school's Mu Alpha Theta chapter, after two years as vice president and competitions
manager. Parliamentarian and secretary for FBLA, programs and operations director for the
International Research Olympiad, and a member of the National Honor Society.

<p align="center">
  <sub>📫 <a href="mailto:ronitkat08@berkeley.edu">ronitkat08@berkeley.edu</a> · Berkeley, CA</sub>
</p>
