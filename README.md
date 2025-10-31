# AIRIX – AI Response Intelligence Exchange
### *Where AI Insights Converge*

**A No-Code Learning Project by:**  
**Muskan Wahi**  
CA Final Student | The Institute of Chartered Accountants of India (ICAI)

---

## 💡 Project Catalyst & Goal

AIRIX was conceptualized to solve a practical inefficiency — switching between multiple AI models (ChatGPT, Gemini, Claude, etc.) for validation and comparison while researching for CA Final and legal topics.

Over a 2-week log, more than **12+ hours monthly** were wasted in repetitive manual AI comparisons.

### 🎯 Objective
To automate this verification loop using a **no-code multi-AI workflow**, targeting **~90% faster research and higher analytical consistency**.

---

## ⚙️ Current Prototype Overview

AIRIX is a **Multi-AI Query Aggregation System** built using **N8N (no-code automation)**.  
It sends one query to multiple AI models (currently ChatGPT + Gemini) and automatically compares their responses to generate a unified summary.

| Component | Description |
| :--- | :--- |
| **Query Models** | ChatGPT & Gemini (2 API keys integrated) |
| **Comparison Logic** | Internal rule-based synthesis (no Claude yet) |
| **Automation Tool** | N8N Desktop |
| **Dashboard Layer** | Lovable.dev (UI under construction) |
| **Efficiency Gain** | ~90% faster vs manual multi-tab process |
| **Status** | Backend complete ✅ → Frontend design in progress 🎨 |

---

## 🧩 System Architecture

**Data Flow:**  
`User Input → Parallel API Requests (ChatGPT + Gemini) → Rule-Based Comparison Logic (N8N) → Output displayed on Lovable.dev dashboard (Prototype UI)`

### 🔁 Scalable by Design
Framework supports future integration of multiple AIs (Claude, DeepSeek, Grok, Meta AI) without redesigning the core workflow.

---

## 🧰 Tech Stack

| Component | Tool | Purpose |
| :--- | :--- | :--- |
| **Workflow Automation** | N8N | Parallel API orchestration |
| **AI Models** | ChatGPT + Gemini | Query engines |
| **Synthesis Logic** | Internal Rule-Based System | Comparative analysis |
| **Dashboard (UI)** | Lovable.dev | Visualization prototype |

---

## 🧠 Key Learning Outcomes

- Understood REST API fundamentals and workflow authentication  
- Built a functioning no-code automation pipeline in N8N  
- Integrated two AI APIs using logical branching and synthesis  
- Designed a scalable proof-of-concept system (prototype → production path)  
- Bridged finance and technology via practical application

---

## 🚀 Setup Instructions

1. Install **N8N Desktop** or run via `npm i -g n8n`.  
2. Obtain API keys for **ChatGPT (OpenAI)** and **Gemini (Google AI Studio)**.  
3. Import the provided `AIRIX_Workflow.json` file into N8N.  
4. Add your keys to the workflow credentials (do **not** commit keys to the repo).  
5. Run the workflow locally or connect to **Lovable.dev** for UI visualization.

> **Security note:** Never commit API keys or `.env` files to GitHub. Use local credentials only.

---

## 🧭 Future Enhancements

- Integrate **Claude API** as an intelligent synthesis engine  
- Add **real-time dashboard publishing** and user authentication  
- Introduce **AI response analytics** (agreement/variance tracking)  
- Enable **query export** (PDF / CSV) for audit trails

---

## 👩‍💻 About the Creator

**Muskan Wahi**  
CA Final Student | ICAI  
Exploring intersections between **finance, automation, and AI**.

📧 **muskanwahi@yahoo.com**  
🔗 [LinkedIn](https://linkedin.com/in/muskan-wahi-687724213/)  
💻 [GitHub](https://github.com/Muskan-Wahi/AIRIX-Multi-AI-Automation-Project)

---

## 📜 License

Licensed under the **MIT License**. See `LICENSE` for details.

---

> *Turning professional inefficiency into innovation — one automated workflow at a time.*
