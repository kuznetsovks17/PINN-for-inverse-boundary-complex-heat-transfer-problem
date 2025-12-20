# 🧪 PHYSICS INFORMED NEURAL NETWORKS FOR SOLVING INVERSE BOUNDARY-VALUE PROBLEMS OF COMPLEX HEAT TRANSFER

**Short abstract (2–4 lines)**  
Describe the scientific problem, method, and main result.

The system describing radiative and conductive heat transfer is considered

$$
\begin{aligned}
\frac{\partial \theta}{\partial t}
- \mathrm{Fo}\,\Delta \theta
+ \mathrm{Fo}\,\Xi_{\mathrm{rad}}
\left( |\theta|\,\theta^3 - \varphi \right)
&= 0, \\[6pt]
- S\,\Delta \varphi
+ \alpha \left( \varphi - |\theta|\,\theta^3 \right)
&= 0, \qquad \mathbf{x} \in \Omega \times [0,1].
\end{aligned}
$$

<p align="center">
  <img src="assets/gifs/overview.gif" width="600">
</p>

---

## 🔬 Problem Statement
Clearly state:
- what problem is addressed
- why it matters scientifically
- limitations of existing methods

---

## 🧠 Methodology
Describe:
- theoretical background
- models / equations
- algorithms

<p align="center">
  <img src="assets/gifs/method.gif" width="600">
</p>

---

## ⚙️ Implementation Details
- Architecture
- Hyperparameters
- Dataset description
- Training procedure

---

## 📊 Results
Quantitative and qualitative results.

<p align="center">
  <img src="assets/gifs/results.gif" width="600">
</p>

---

## 📈 Experiments
| Experiment | Description | Outcome |
|----------|-------------|---------|
| Exp 1 | Baseline | Accuracy 92% |
| Exp 2 | Improved model | Accuracy 96% |

---

## 🧪 Reproducibility
```bash
git clone https://github.com/USERNAME/REPO.git
cd REPO
pip install -r requirements.txt
jupyter notebook
