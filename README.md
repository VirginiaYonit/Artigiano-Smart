# Agent Artigiano
A simple, modular AI agent for small businesses.  
No code required: business logic lives in documents, not in code.

<img width="744" height="524" alt="image" src="https://github.com/user-attachments/assets/86c537d3-678e-4426-b7e1-53877fdbe957" />

🔗 [Try the demo on Hugging Face](https://huggingface.co/spaces/virginialevy/artigiano-smart)


## Challenge  
I developed “Agent Artigiano”, a micro-AI agent tailored for small businesses.  
The agent uses the **Persona Pattern** to simulate expert reasoning (accounting, document handling, customer service) and relies on **modular tools** that can be updated by anyone — not just developers.

## Approach  
Repeatable processes, fewer errors, and greater autonomy for business owners.  
Business logic stays transparent: just update the document, not the code.  
The agent can be extended with new tools and features without starting from scratch.

## Outcome  
Agent Artigiano bridges the gap between “AI for big enterprises” and the **real needs of artisans and small businesses**.  
Leveraging the document-as-implementation pattern and modular tool design makes this solution **sustainable, flexible**, and always aligned with real-world priorities.

---

## 🔧 Extending Agent Artigiano — Example Tool: PDF Generator  
As part of the agent’s evolution, I developed an additional tool for small businesses:  

### 🗂️ AI Multi-Product PDF Generator – Bilingual Product Sheet Automation  
An automated system that creates professional product sheets in **Italian and English** from an Excel file.  
It combines Generative AI (text), image integration, and layout with **ReportLab**.

**Features:**
- 🔤 Description generation via LLMs  
- 🖼️ Product image support (with fallback if missing)  
- 🧾 Elegant layout using ReportLab  
- 🌍 Language switching logic  
- 📄 Multipage and batch-ready  
- 🧩 Fully modular and customizable  

**Use case:**  
This tool fits within the Agent Artigiano ecosystem as a specialized module for e-commerce or catalog-based businesses who need to **generate high-quality product communication** quickly, efficiently, and without technical skills.

The PDF Generator is already fully integrated with Agent Artigiano and can be used to create elegant, multilingual product sheets on demand, directly from the agent’s logic, no coding required.

⚙️ The underlying code for the PDF Generator is not included in this repository.
The tool is fully functional and demonstrated in the sample files below.
Agent Artigiano is licensed under MIT, while the PDF module remains proprietary for now.

---

## Why it matters  
Based on agent design best practices — the “MATE” principles (Model, Action, Token, Environment).  
Fully customizable for any business sector, no technical lock-in.  
Simple to update: business logic lives in human-readable documents, not in code.

---

## 🧭 Methodology – How Agent Artigiano Was Built
Agent Artigiano is the result of a design-driven AI process grounded in transparency, modularity, and real-world usability.
Rather than following a top-down “developer-only” approach, I worked iteratively using:

🧩 Modular architecture: tools are built independently and integrated via documents

🗣️ Prompt engineering and pattern testing: using the Persona Pattern to simulate expert reasoning

📄 Document-as-code: all business rules are defined in natural language documents

👂 Feedback loop: tested with real use cases and iteratively refined based on constraints and needs

This approach reflects the principles of civic testing and responsible AI design: intelligibility, flexibility, and human-in-the-loop collaboration.

---

🤖 Built with ChatGPT – My Invisible Partner
Agent Artigiano was developed in close collaboration with ChatGPT, which acted as:

A coding assistant, helping translate complex logic into Python tools

A co-designer, supporting architectural and UX choices

A testing partner, evaluating reasoning patterns and generating structured prompts

A documentation sparring partner, helping write clear, useful, and honest technical descriptions

This README — and many other parts of the project — are the result of human–AI collaboration, grounded in reflection, iteration, and transparency.

---

### Curious how a micro-AI agent could help your business?  
[Contact me](https://www.linkedin.com/in/virginia-levy-abulafia/) | [Try the Demo](https://huggingface.co/spaces/virginialevy/artigiano-smart)
