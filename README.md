# PROMPT-FORAGE-AGENT
PromptForge is an Enterprise Prompt Economics tool that transforms vague input into high-accuracy, token-minimized instructions. Using an "Agentic Interrogator," it resolves intent before generating a Master Prompt and a compressed Eco-Prompt. Slash API costs by up to 60% with real-time FinOps tracking and multi-modal reverse engineering.
# ⚒️ PromptForge: Enterprise Prompt Economics & Intent Resolution

**PromptForge** is an intelligent AI middleware designed to bridge the gap between vague human intent and high-performance LLM execution. 

In enterprise environments, "prompt bloat" and ambiguous instructions lead to two major failures: **excessive API costs** (token waste) and **AI hallucinations**. PromptForge solves this through a "Human-in-the-Loop" workflow that clarifies intent and mathematically compresses instructions for maximum FinOps efficiency.



---

## 🚀 Core Features

### 1. Agentic Intent Resolution (The Interrogator)
Intercepts vague 5-word inputs and pauses to ask **2-3 highly targeted clarifying questions** (e.g., "What is the target audience?", "What format is required?"). This ensures the LLM never has to "guess."

### 2. Dual-Prompt Generation
The system generates two distinct outputs for every request:
* **The Master Prompt:** A high-fidelity, perfectly structured instruction set for maximum accuracy.
* **The Eco-Prompt:** A token-compressed version that strips conversational filler ("please", "can you", redundant adjectives) while maintaining 100% technical logic density.

### 3. FinOps & Token Economics Dashboard
A live UI component that compares the character/token length of a standard prompt versus the **Eco-Prompt**, calculating the exact percentage of API cost saved per run (e.g., “Tokens Saved: 58%”).

### 4. Multi-Modal Reverse Engineering
A specialized module where users can upload a final asset (image or text block). The vision model "de-renders" the asset to generate the exact prompt needed to recreate it.

---

## ⚙️ The Working Mechanism (The Agentic Loop)

1.  **Ingestion:** User enters a raw idea (e.g., "Write a team email about the update").
2.  **Interception:** Backend analyzes the text and returns 3 clarifying questions in **JSON format**.
3.  **Refinement:** User provides context (Tone: Urgent, Audience: Devs, Length: <100 words).
4.  **The Forge:** The system stitches the data into a **Master Prompt**.
5.  **Algorithmic Compression:** An optimization filter rewrites the instructions into high-density key-value pairs to minimize token count.
6.  **Analytics:** The UI renders the "Money/Tokens Saved" metric based on the delta between the two prompts.



---

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3 (Tailwind CSS), Vanilla JavaScript.
* **UI Style:** Glassmorphic / Enterprise Dark Mode.
* **AI Engine:** Google Gemini 1.5 Flash (via REST API) for high-speed, low-cost inference.
* **Vision:** Multimodal API endpoints for Base64 image analysis.

---


