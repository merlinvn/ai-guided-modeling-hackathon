# 🧪 AI-Guided SIR Modeling Hackathon

This repository hosts materials for the **AI-Guided SIR Modeling Hackathon**, a short, hands-on hackathon focused on **epidemiological modeling, parameter inference, and AI-assisted scientific coding** using **Python, Google Colab, and ChatGPT**.

The hackathon is designed to be **beginner-friendly**, reproducible, and suitable for short courses, workshops, or training sessions.

---

## 🎯 Hackathon Overview

In this hackathon, participants will:

- Build a **Susceptible–Infected–Recovered (SIR)** model from scratch
- Simulate epidemic outbreaks using ordinary differential equations (ODEs)
- Estimate key epidemiological parameters (β, γ, R₀)
- Fit models to real outbreak data using:
  - Least squares
  - Likelihood-based inference (Poisson)
- Learn how to use **ChatGPT effectively** as a coding and reasoning assistant

All work is done in **Google Colab** — no local installation required.

---

## 📊 Dataset

The hackathon uses **real outbreak data**:

- **Disease:** Measles
- **Location:** Niamey, Niger
- **Source:** Grais et al. (2006)
- **Data type:** Biweekly measles case counts
- **Communities:** Three (A, B, C)

Time is measured in **biweeks**, and the modeling assumptions reflect this structure.

---

## 👥 Pre-Hackathon Documentation

Please read the appropriate guide **before** the hackathon.

### 🔹 For Participants

👉 **Participant Guide (Pre-Hackathon)**  
📄 `docs/participants.md` _(updating)_

This guide explains:

- Hackathon format and agenda
- Required tools and setup
- Dataset description
- What you will build during the hackathon
- How ChatGPT will be used

---

### 🔹 For Organizers

👉 **Organizer Guide (Pre-Hackathon)**  
📄 `docs/organizers.md` _(updating)_

This guide covers:

- How to prepare the Google Colab notebook
- Required datasets and materials
- Pre-recorded ChatGPT demos
- Suggested facilitation flow
- Post-hackathon deliverables

---

## 📁 Repository Structure

```text
.
├── README.md
├── data/
│   └── niamey.csv
├── notebooks/
│   └── sir_hackathon.ipynb
├── docs/
│   ├── participants.md
│   └── organizers.md
├── prompts/
│   └── chatgpt_prompts.md
└── slides/
    └── hackathon_slides.pdf
```

_(Some files may be added incrementally as the hackathon materials are finalized.)_

---

## 🛠 Tools Used

- Python 3
- Google Colab
- NumPy, SciPy, pandas, matplotlib
- ChatGPT (LLM-assisted coding and explanation) or Google Gemini

---

## 🚀 After the Hackathon

Participants will leave with:

- A fully runnable SIR modeling notebook
- Practical experience in epidemic inference
- Reusable ChatGPT prompt patterns for scientific coding
- Ideas for extending models (SEIR, stochastic models, Bayesian inference)

---

## 📌 License & Use

This repository is intended for **educational and training purposes**.
Please check the dataset source for any specific citation requirements.

---

## 🤝 Contributing

Contributions, improvements, and extensions are welcome.
If you plan to reuse this hackathon for teaching or training, feel free to fork and adapt the materials.

---

We look forward to hacking epidemic models **with AI** together.
