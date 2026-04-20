# 🛡️ Cyber Reachability Sentinel

### *Transitive Closure Analysis for Network Security using Warshall’s Algorithm*

---

## 🚀 Overview

**Cyber Reachability Sentinel** is a web-based tool that analyzes network connectivity using concepts from **Discrete Mathematics**.
It models servers as a **directed graph** and applies **Warshall’s Algorithm** to detect **indirect attack paths** and hidden vulnerabilities.

> 💡 *Not just who is connected — but who can eventually be reached.*

---

## 🧠 Core Concepts Used

* 📌 **Graph Theory** (Nodes & Directed Edges)
* 📌 **Adjacency Matrix Representation**
* 📌 **Binary Relations**
* 📌 **Warshall’s Algorithm**
* 📌 **Transitive Closure**

---

## ⚙️ How It Works

1. **Add Servers (Nodes)**

   * Example: `WEB_01`, `APP_01`, `DB_01`

2. **Define Connections (Edges)**

   * Example: `WEB_01 → APP_01`

3. **Run Analysis**

   * Click: **Generate Full Reachability Map**

4. **Output Generated**

   * ✔ Direct + Indirect reachability
   * ✔ Attack paths
   * ✔ Reachability matrix
   * ✔ Threat level

---

## 🔍 Example

### Input:

```
WEB_01 → APP_01  
APP_01 → DB_01
```

### Output:

```
WEB_01 can attack: WEB_01, APP_01, DB_01
APP_01 can attack: APP_01, DB_01
DB_01 can attack: DB_01
```

👉 Shows **indirect path**:
**WEB_01 → APP_01 → DB_01**

---

## ⚠️ Threat Interpretation

| Scenario                | Meaning     |
| ----------------------- | ----------- |
| Limited connections     | 🟢 Safe     |
| Indirect paths present  | 🟡 Elevated |
| Fully connected (cycle) | 🔴 Critical |

---

## 📊 Features

* ⚡ Real-time reachability analysis
* 🧮 Automatic adjacency matrix generation
* 🔁 Transitive closure computation
* 🚨 Threat level detection
* 💻 Clean cyber-style UI

---

## 🖥️ Tech Stack

* **HTML**
* **Tailwind CSS**
* **JavaScript (Vanilla)**

---

## 📂 Project Structure

```
Cyber-Reachability-Sentinel/
│
├── index.html
├── README.md
└── screenshots/
```

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/cyber-reachability-sentinel.git
```

2. Open `index.html` in browser

👉 No installation required

---

## 🌐 Live Demo (Optional)

Add your Vercel/Netlify link here

---

## 🎯 Learning Outcome

This project demonstrates how **Discrete Mathematics** can be applied to:

* Network Security
* Dependency Analysis
* Vulnerability Detection

---

## 🧠 Key Insight

> “Warshall’s Algorithm transforms a relation into its transitive closure, revealing all reachable paths in a network.”

---


---

