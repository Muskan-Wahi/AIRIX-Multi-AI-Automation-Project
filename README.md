# AIRIX – AI Response Intelligence Exchange  
### Where AI Insights Converge  

**A No-Code Learning Project by:** Muskan Wahi  
CA Final Student | The Institute of Chartered Accountants of India (ICAI)  

---

## 💡 Project Catalyst & Goal  

AIRIX originated from a recurring professional frustration — the inefficiency of verifying information across multiple AI models while preparing for CA Final exams.  
Over a 2-week log, more than **12 hours monthly** were lost to repetitive manual comparisons of AI responses.

### 🎯 The Objective  
To automate this validation loop using a **no-code, multi-AI workflow**, achieving ~90% faster research while maintaining analytical accuracy.

---

## ⚙️ Project Overview  

AIRIX is a **Multi-AI Query Aggregation System** that sends a single query to multiple AI models, compares their outputs, and highlights consensus, contradictions, and unique insights — all in one view.

**Key Functionality:**
1. **Parallel Querying:** Sends the same query to **ChatGPT** and **Gemini** simultaneously.  
2. **Rule-Based Comparison:** Logical synthesis layer (coded in N8N) performs structured output validation.  
3. **Unified Output:** Consolidates both responses for faster, more reliable analysis.

---

## 🧠 Current Prototype Scope  

| Component | Description |
| :--- | :--- |
| **Query Models** | ChatGPT & Gemini (queried in parallel) |
| **Comparison Logic** | Internal (Rule-Based) synthesis – no external Claude API used yet |
| **Automation Tool** | N8N (no-code workflow builder) |
| **Efficiency Gain** | ~90% faster than manual multi-tab comparison |
| **Status** | Design complete → Prototype preparation in progress |

---

## 🧩 System Architecture  

**Technical Flow:**  
User Query → Parallel API Requests (ChatGPT + Gemini)
→ Rule-Based Comparison Layer → Unified Output Dashboard (Lovable.dev)                                                                                                                                             
### 🔁 Designed for Scalability  
The system is modular — it can scale to integrate **any number of AI models** (e.g., Claude, DeepSeek, Grok, Meta AI) without redesigning the core workflow.

---

## 🧾 Key Learning Outcomes  
- Learned fundamentals of REST API authentication  
- Designed modular no-code workflows in N8N  
- Practiced prompt structuring and comparative synthesis  
- Bridged **financial reasoning** with **AI automation**  
- Developed analytical optimization mindset  

---

## 🧰 Tech Stack  

| Component | Tool | Purpose |
| :--- | :--- | :--- |
| **Workflow Automation** | N8N | No-code orchestration |
| **Query Models** | ChatGPT & Gemini | Parallel reasoning |
| **Comparison Logic** | Internal (Rule-Based) | Output validation |
| **Dashboard** | Lovable.dev | Planned visualization layer |

---

## 🚀 Setup & Deployment  

1. Install **N8N** (Desktop App, Docker, or Cloud).  
2. Obtain API keys for ChatGPT and Gemini.  
3. Import `AIRIX_Workflow.json` into N8N.  
4. Update credentials in workflow nodes.  
5. Run the workflow with your desired query.  

---

## 🧭 Future Enhancements  
- Integration of Claude for synthesis and summarization  
- Cost tracking per query  
- PDF/CSV export for audit logs  
- Model-level performance analytics  

---

## 👩‍💻 About the Creator  

**Muskan Wahi**  
CA Final Student | ICAI  
Independent learner exploring how AI automation intersects with finance, law, and strategic analysis.  
📧 muskanwahi@yahoo.com  
💼 [linkedin.com/in/muskan-wahi-687724213](https://linkedin.com/in/muskan-wahi-687724213)  

---

## 📜 License  

Licensed under the **MIT License**.  
You are free to use, modify, and distribute this project with appropriate credit.  

---

> “Bridging the gap between traditional professional analysis and emerging AI automation — one validated query at a time.”
