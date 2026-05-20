# 🚀 Springboard Data Science Course — Project Portfolio

> A curated collection of hands-on Python projects completed during the **Springboard Data Science Bootcamp**, covering the full arc from statistical inference to machine learning and a real-world capstone.

---

## 🧠 What's Inside

This repository is organized as a set of self-contained projects, each tackling a different dimension of data science:

| Folder | Topic | Methods |
|---|---|---|
| `EDA_human_temperature` | Is 98.6°F really the normal human body temperature? | EDA, bootstrapping, hypothesis testing |
| `EDA_racial_discrimination` | Does race influence callback rates for job applications? | Chi-square test, frequentist & Bayesian inference |
| `Statistical_Inference_Hypotheis_Test` | Frequentist vs. Bayesian statistical inference | Hypothesis testing, p-values, confidence intervals |
| `InfStatCP` | Inferential statistics capstone | End-to-end statistical analysis |
| `boston_linear_regression` | Predicting housing prices in Boston | OLS linear regression, feature selection |
| `hospital_readmit` | Predicting hospital readmission rates | Classification, logistic regression |
| `JSON-Based-Data-Exercises-master` | Working with real-world JSON data sources | Data wrangling, Pandas, nested structure parsing |
| `Miniprojects` | Bite-sized explorations across the curriculum | Mixed: SQL, APIs, NLP, visualization |
| `CapStoneProject` | Full end-to-end data science project | Complete ML pipeline |

---

## 🔬 Scientific Method at the Core

Every project in this repo follows a disciplined analytical approach:

1. **Observation** — Identify a real-world question or dataset anomaly worth investigating
2. **Hypothesis** — Formulate a testable statistical claim
3. **Experimentation** — Apply appropriate statistical tests or ML models
4. **Analysis** — Interpret results with rigor (p-values, confidence intervals, error metrics)
5. **Conclusion** — Draw evidence-based conclusions and acknowledge limitations

---

## 🛠️ Tech Stack

```
Python 3.x
├── pandas          — data wrangling
├── numpy           — numerical computing
├── matplotlib      — visualization
├── seaborn         — statistical graphics
├── scipy.stats     — hypothesis testing
├── sklearn         — machine learning
└── jupyter         — interactive notebooks
```

---

## 📈 Highlighted Projects

### 🌡️ Human Body Temperature — EDA & Inference
**Question**: Is the mean human body temperature actually 98.6°F as Wunderlich claimed in 1851?  
**Approach**: Bootstrap sampling + CLT-based z-test on a real clinical dataset.  
**Result**: Evidence suggests the true population mean may be closer to 98.25°F.

### ⚖️ Racial Discrimination in Hiring
**Question**: Do Black-sounding names receive fewer callbacks than White-sounding names on identical CVs?  
**Approach**: Chi-square test of independence + margin-of-error analysis.  
**Result**: Statistically significant evidence of differential callback rates.

### 🏠 Boston Housing — Linear Regression
**Question**: Which neighbourhood features best predict median house prices?  
**Approach**: OLS regression with feature importance analysis.  
**Result**: Per-capita crime rate and lower-status population % are the strongest negative predictors.

---

## 🚦 Getting Started

```bash
# Clone the repo
git clone https://github.com/alketcecaj12/springboardcourse.git
cd springboardcourse

# Launch any notebook
jupyter notebook EDA_human_temperature/
```

All notebooks are self-contained — datasets are either included or loaded via public URLs.

---

## 👤 About

Built by [Alket Cecaj](https://github.com/alketcecaj12) — data scientist and quantitative analyst with a PhD in Industrial Innovation Engineering. This repo documents the Springboard journey through applied statistics, machine learning, and real-world data problem solving.

---

*"Without data, you're just another person with an opinion."* — W. Edwards Deming
