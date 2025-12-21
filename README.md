# 🧪 PHYSICS INFORMED NEURAL NETWORKS FOR SOLVING INVERSE BOUNDARY-VALUE PROBLEMS OF COMPLEX HEAT TRANSFER

**Short abstract (2–4 lines)**  
Describe the scientific problem, method, and main result.

The system describing radiative and conductive heat transfer is considered


```math
\frac{\partial \theta}{\partial t}-\textrm{Fo}\Delta\theta + \textrm{Fo}\Xi_{rad}(|\theta|\theta^3-\varphi)=0, 
```
```math
-S\Delta \varphi +\alpha (\varphi - |\theta|\theta^3)=0, \;\;\;\mathbf{x}\in\Omega\times[0,1].
```
```math
\theta|_{t=0}=\theta_0,
```
```math
\frac{\partial \theta}{\partial n} + \textrm{Bi}(h)(\theta-\theta_b)=0, \;\;\; S\frac{\partial \varphi}{\partial n} + \gamma(\varphi-\theta_b^4)=0 \;\;\;\textrm{on}\;\Gamma,
```
Here $\theta$ is the dimensionless temperature and $\varphi$ is the average radiation intensity, $Bi(h)$ - is the Biot number, $h$ - is the boundary heat transfer coefficient, $\gamma$ - is the boundary surface reflection coefficient .

For inverse problem $\theta$, $\varphi$, $h$, $\gamma$ are unknown functions. An a priori information in form of temperature values at observation pointss is known.

<p align="center">
  <img src="NE1/images/domain.png" width="250">
  <img src="NE2/images/domain.png" width="250">
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
