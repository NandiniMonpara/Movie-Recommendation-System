# Movie-Recommendation-System
Movie Recommendation System using Markov Decision Process

# 🎬 Movie Recommendation System using Markov Decision Process (MDP)

A smart movie recommendation engine that models user behavior as a sequential decision-making process using **Markov Decision Process (MDP)**. This system simulates genre transitions, learns user preferences, and recommends the next best movie or genre to watch based on long-term user satisfaction.

---

## 🧠 What is MDP?

A Markov Decision Process is a mathematical framework for modeling decision-making where outcomes are partly random and partly under the control of a decision-maker. It's widely used in AI for planning and reinforcement learning.

In this project:
- **States** represent movie genres or movies
- **Actions** are possible next genres or movies
- **Transition Probabilities** capture how users switch between genres
- **Rewards** represent user satisfaction (e.g., ratings)
- **Policy** is the recommendation strategy

---

## 📌 Key Features

- 🔁 Models user viewing behavior with state transitions
- 🎯 Recommends optimal next genre or movie using Value Iteration
- 📈 Simulates long-term user satisfaction, not just immediate preferences
- 📊 Visualizes transition probabilities and policy convergence

---

## 🚀 Tech Stack

- Python
- NumPy & Pandas – data manipulation
- Value Iteration – core MDP algorithm
- Matplotlib & Seaborn – visualization

---


