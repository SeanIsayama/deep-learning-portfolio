# 🧠 Deep Q-Learning for Competitive Tank Battles

**CSE 151B – Deep Learning**  
**Winter 2025 @ UC San Diego**  
**Final Project**

- 📄 [View Report (PDF)](./report.pdf)  
- 🔒 Code available upon request (private repository, per course policy)

---

## 📌 Overview

In this open-ended project, we developed a reinforcement learning agent to play a custom 2D tank battle game using Deep Q-Learning. Key aspects included:

- Designing a dynamic adversarial environment in PyGame with aim, shoot, and dodge mechanics
- Implementing and comparing multiple RL strategies:
  - Standard DQN vs. Dueling DQN
  - Curriculum learning and reward shaping
  - PPO and Imitation Learning (experimental)
- Engineering reward functions to encourage accuracy, survival, and strategy
- Evaluating agents against human players, random bots, and heuristic opponents
- Visualizing training progression via Q-values and episodic reward curves

---

## 👨‍👩‍👧‍👦 Team Members

- **Hikaru Isayama**
- **Avi Mehta**
- **Wilson Liao**
- **Julia Wong**
- **Sean Z.**

---

## 🛠 My Contributions (Hikaru Isayama)

- Helped develop base DQL model, and performed debugging thought group programming
- Contributed to engineering and tuning curriculum learning & epsilon scheduling
- Helped create custom reward functions for offense and defense
- Contributed to evaluation framework and report writing

---

## ✅ Results

- Agent won **6/10 matches** vs. a random bot, but struggled against heuristic and human opponents
- Standard DQN agent learned dodging behavior after 60K steps
- Dueling DQN showed instability in Q-value estimates and failed to converge
- Demonstrated the importance of architectural choices, reward design, and training scale

---

## ⚠️ Academic Policy

This project was completed for academic credit. Code is not public to preserve course integrity but is available upon request for recruiting purposes.