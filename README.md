# 🤖 RL-Based Cloud Load Balancer

A **Reinforcement Learning-powered Load Balancer** that intelligently distributes computational workloads across multiple servers using **Google Cluster Data**. Built with **Python, Stable-Baselines3, FastAPI**, and fully deployable in **Google Colab** with live visualization and REST API support.

<p align="center">
  <img src="https://img.shields.io/badge/AI-RL Load Balancer-blueviolet" />
  <img src="https://img.shields.io/badge/Framework-FastAPI-green" />
  <img src="https://img.shields.io/badge/Colab-Ready-orange" />
  <img src="https://img.shields.io/badge/Status-Production Ready-brightgreen" />
</p>

---

## 🚀 Live Demo

> 👉 Run the full project with **just one cell in Google Colab**!  
> View the real-time dashboard, schedule jobs, and test the REST API.

---

## 📌 Features

✅ **End-to-End Google Colab Support**  
✅ **Custom Load Balancer Gym Environment**  
✅ **AI Agent using Proximal Policy Optimization (PPO)**  
✅ **Performance Comparison with Round Robin & Random**  
✅ **Interactive Web API using FastAPI**  
✅ **Ngrok Integration for Live Sharing**  
✅ **Real-Time Dashboard with Auto-Updating Server Metrics**  
✅ **Modular and Extensible Architecture**

---

## 🧠 How It Works

### 1. Environment
Simulates a realistic cloud environment with:
- Resource-constrained servers (CPU & memory)
- Jobs having dynamic arrival, duration, and requirements
- Overload detection and penalty-based reward functions

### 2. AI Agent
- Trained using PPO via `stable-baselines3`
- Optimizes load balancing by minimizing resource over-utilization and standard deviation

### 3. Web API
- Exposes endpoints to:
  - Schedule jobs (`POST /schedule`)
  - Get server status (`GET /status`)
  - View real-time statistics (`GET /stats`)
  - Access interactive dashboard (`GET /demo`)

---

## 📈 Performance Comparison

| Strategy       | Score ↑ (Higher is Better) |
|----------------|----------------------------|
| 🧠 AI (PPO)     | ✅ Best Performance         |
| 🔁 Round Robin | Moderate                   |
| 🎲 Random      | Least Efficient            |

> AI outperforms traditional heuristics by learning to optimally allocate jobs based on real-time load patterns.

---

## ⚙️ Installation & Usage

### ▶️ Run in Google Colab

Copy the contents of the `.py` file into a single Colab cell and run.

You’ll see:

- 📊 Sample data generated  
- 🧠 AI model trained  
- 📈 Performance charts  
- 🌐 Web API launched  
- 💻 Public URL via Ngrok

---

## 📡 API Endpoints

| Endpoint      | Method | Description                |
|---------------|--------|----------------------------|
| `/`           | GET    | Welcome message & docs     |
| `/schedule`   | POST   | Schedule a job             |
| `/status`     | GET    | Real-time server load      |
| `/stats`      | GET    | Load balancer statistics   |
| `/demo`       | GET    | Interactive UI Dashboard   |

---

## 📂 File Overview

