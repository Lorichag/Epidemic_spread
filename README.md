# 🦠 Epidemic Spread Simulation using NetLogo

## 📌 Project Overview

This project implements an **Agent-Based Model (ABM)** to simulate the spread of an infectious disease within a population. The model is inspired by real-world epidemics such as COVID-19 and follows a simplified **SIR (Susceptible–Infected–Recovered)** framework, extended with additional features like vaccination and social distancing.

The goal is to analyze how different parameters affect disease propagation and to observe emergent behaviors in the system.

---

## 🎯 Objectives

* Simulate disease transmission between individuals
* Analyze the impact of:

  * Infection rate
  * Recovery time
  * Initial number of infected individuals
  * Vaccination rate
  * Social distancing
* Visualize epidemic dynamics using plots

---

## 🧠 Model Description

### Agents

Each agent (turtle) represents an individual and can be in one of the following states:

* 🟢 Susceptible (S)
* 🔴 Infected (I)
* 🔵 Recovered (R)
* 🟡 Vaccinated (V)

### Environment

* A 2D grid where agents move randomly
* Agents interact locally within a certain radius

### Rules

* **Movement**: Agents move randomly, with optional social distancing behavior
* **Infection**: Susceptible agents may become infected when near infected agents
* **Recovery**: Infected agents recover after a certain period
* **Vaccination**: A portion of the population is vaccinated at the start and cannot be infected

---

## ⚙️ Parameters (Interface Controls)

| Parameter          | Description                               |
| ------------------ | ----------------------------------------- |
| `infection-rate`   | Probability of disease transmission       |
| `initial-infected` | Number of infected agents at start        |
| `recovery-time`    | Time steps before recovery                |
| `vaccination-rate` | Percentage of vaccinated population       |
| `social-distance`  | Distance at which agents avoid each other |

---

## ▶️ How to Run the Simulation

### 1. Install NetLogo

Download and install NetLogo from the official website:
👉 https://ccl.northwestern.edu/netlogo/

---

### 2. Open the Project

* Launch NetLogo
* Click **File → Open**
* Select the `.nlogo` file from this project

---

### 3. Run the Simulation

1. Click the **`setup`** button
   → Initializes the population

2. Adjust parameters using the sliders (optional)

3. Click the **`go`** button
   → Starts the simulation

---

### 4. Observe Results

* The simulation runs in real-time
* The plot displays:

  * Number of Susceptible agents
  * Number of Infected agents
  * Number of Recovered agents
  * Number of Vaccinated agents

---

## 🧪 Experiments

You can explore different scenarios by modifying parameters:

### Example Experiments

* Increase `infection-rate` → faster spread
* Increase `vaccination-rate` → reduced infections
* Increase `social-distance` → slower transmission
* Change `recovery-time` → affects epidemic duration


