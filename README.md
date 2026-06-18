# 💊 Drug Metabolism Modeling and Simulation

Mathematical modeling and numerical simulation of drug metabolism using ordinary differential equations (ODEs).

---

## 📖 Overview

This project develops mathematical models to investigate the dynamic behavior of drug concentration under different administration methods, including **intravenous injection** and **oral administration**.

Using ordinary differential equations (ODEs), numerical simulation, and stability analysis, the project compares different metabolism mechanisms and analyzes how model parameters influence drug concentration over time.

---

## 🎯 Objectives

- Model drug concentration dynamics using ODEs
- Compare intravenous and oral drug delivery
- Perform numerical simulation using Euler's Method
- Analyze equilibrium points and system stability
- Conduct parameter sensitivity analysis

---

## 🔬 Methodology

### 1. Intravenous Injection Model

The drug concentration is modeled as

\[
\frac{dA}{dt}=r-cA
\]

where

- \(A\): drug amount in the body
- \(r\): injection rate
- \(c\): metabolism rate

The analytical solution and long-term equilibrium behavior are derived and analyzed.

---

### 2. Oral Administration Model

An oral drug absorption process is incorporated to describe delayed drug concentration changes after administration.

The model compares concentration curves between oral delivery and continuous intravenous injection.

---

### 3. Logistic Metabolism Extension

To better represent saturation effects in drug metabolism, the linear metabolism term is extended to a logistic form.

The project investigates

- equilibrium points
- local stability
- long-term system behavior

under different parameter settings.

---

### 4. Numerical Simulation

Euler's Method is implemented in R to simulate drug concentration trajectories and validate analytical results.

Different parameter combinations are tested to study their effects on drug dynamics.

---

## 📊 Key Results

- Built ODE-based pharmacokinetic models for different drug administration methods.
- Compared concentration evolution under intravenous and oral delivery.
- Performed equilibrium and stability analysis of nonlinear metabolism models.
- Conducted parameter sensitivity analysis to investigate the influence of metabolism rate and carrying capacity.
- Visualized drug concentration trajectories using R.

---

## 🛠️ Tech Stack

- **R**
- Ordinary Differential Equations (ODE)
- Euler Numerical Simulation
- Mathematical Modeling
- Stability Analysis
- Data Visualization

---

## 📁 Repository Structure

```
drug-metabolism-modeling/
│
├── README.md
├── report.pdf
└── report.Rmd
```

---

## 🎓 Skills Demonstrated

- Mathematical Modeling
- Dynamic Systems
- Numerical Methods
- Scientific Computing
- Data Visualization
- Problem Formulation

---

## 👨‍💻 Author

**Bowen Zheng**

Master of Data Science and Artificial Intelligence

University of Waterloo
