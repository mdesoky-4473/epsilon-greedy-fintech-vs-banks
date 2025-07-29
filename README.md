# epsilon-greedy-fintech-vs-banks

## 🎯 Overview

This repository contains a Python simulation exploring how an agent makes choices between a traditional bank and a fintech product using the **epsilon-greedy algorithm**. It shows how **early exploration** and **time-discounted rewards** impact long-term returns when fintech has a slightly better expected payoff.

The project supports the blog post:
📖 **[Fintech vs. Banks: Why Early Exploration Unlocks Better Returns](#)**
(Wake Forest School of Professional Studies)

---

## 📊 Key Concepts

* **Epsilon-Greedy Strategy**: Balances exploration (trying new options) with exploitation (sticking with what works).
* **Time-Discounted Rewards**: Rewards lose value the later they are discovered, modeled with a discount factor γ.
* **Simulation Goal**: Understand when and how exploration leads to higher cumulative returns with time sensitivity.

---

## ⚙️ Parameters

* `expected_rewards = [0.05, 0.06]` → Traditional bank vs. fintech product
* `gamma = 0.9999` → Discount factor for time-sensitive decisions
* `epsilons = [...]` → A range of exploration rates (from 0 to 0.4)
* `steps = 500000` → Total time steps per run
* `runs_per_epsilon = 100` → Averaging results over multiple runs

---

## 📈 Visual Outputs

The simulation generates:

* A **combined line chart** showing cumulative discounted returns for banks and fintechs across different epsilon values.
* A **reward gap chart** showing the difference (fintech minus bank) at each exploration level.
* A summary **table** of all results.

---

## ▶️ How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/YOUR_USERNAME/epsilon-greedy-fintech-vs-banks.git
   cd epsilon-greedy-fintech-vs-banks
   ```

2. Install dependencies (requires Python 3.x):

   ```bash
   pip install numpy pandas matplotlib seaborn
   ```

3. Run the script:

   ```bash
   python simulate.py
   ```

Or launch the **Jupyter Notebook** for interactive exploration.

---

## 🏫 Affiliation

Developed as part of applied learning in the
**Wake Forest University – School of Professional Studies (SPS)**
Program in Financial Technology & Analytics (MFTA)

---

## 🏷️ Tags

`#Fintech` `#EpsilonGreedy` `#AIinFinance` `#MachineLearning` `#ExplorationVsExploitation` `#WakeForestSPS`

---

Let me know if you'd like a starter `simulate.py` or `notebook.ipynb` file scaffold as well.
