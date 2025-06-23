# Data Visualization Course

This repository gathers the lab assignments I completed during the **Data Visualization / Exploratory Data Analysis (EDA)** course. Each notebook walks through a compact end‑to‑end workflow: loading and cleaning raw data, exploring patterns with rapid sketches, and finishing with publication‑ready visuals and concise commentary.

Together, the labs show that I can

- profile unfamiliar datasets with **pandas** and **numpy**;
- pick chart types that match the question (bar, histogram, line, network diagrams, etc.) and adjust the styling for clarity;
- surface insights in well‑structured Markdown cells so the story is easy to follow;
- keep notebooks reproducible and lightweight (large CSVs are stored via Git LFS and ignored in Git history).

---

## Structure

| Folder             | Notebook             | Topic                                           |
| ------------------ | -------------------- | ----------------------------------------------- |
| **Animal‑Shelter** | `notebook.ipynb`     | EDA of Austin Animal Center intake/outcome data |
| **PID‑Network**    | `assignment02.ipynb` | Prague public‑transport (PID) network analysis  |

---

## Quick Start

```bash
# 1  Clone
git clone git@github.com:RustemSan/Data-Visualization-Course.git
cd Data-Visualization-Course

# 2  Create / activate an env (optional)
python -m venv .venv && source .venv/bin/activate

# 3  Install minimal stack and launch
pip install pandas matplotlib seaborn jupyterlab
jupyter lab
```



---
