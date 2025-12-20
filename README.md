# 🧪 PHYSICS INFORMED NEURAL NETWORKS FOR SOLVING INVERSE BOUNDARY-VALUE PROBLEMS OF COMPLEX HEAT TRANSFER

**Short abstract (2–4 lines)**  
Describe the scientific problem, method, and main result.

The system describing radiative and conductive heat transfer is considered

$$
\frac{\partial \theta}{\partial t}-\textrm{Fo}\Delta\theta + \textrm{Fo}\Xi_{rad}(|\theta|\theta^3-\varphi)=0,
$$
$$

-S\Delta \varphi +\alpha (\varphi - |\theta|\theta^3)=0, \;\;\;\mathbf{x}\in\Omega\times[0,1].
\end{equation}
$$
Here $\theta$ is the dimensionless temperature, $\varphi$ is the average radiation intensity.


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
