# Stevie: Self-Hosted AI Music Theory Assistant

Stevie is an autonomous, self-hosted AI response agent designed to act as an interactive guitar music theory instructor. By bridging a localized knowledge base with an automated workflow engine, Stevie delivers precise, context-aware answers to complex music theory and guitar layout questions.

---

## 🛠️ System Architecture & Tech Stack

Stevie is built using a decoupled, modular architecture hosted entirely within a localized environment. 

*   **Knowledge Base / Frontend:** Built on a comprehensive music theory wiki platform containing structured data on scales, modes, chord constructions, and fretboard geometry.
*   **Automation & Integration Engine:** Managed via a workflow automation platform (Chatwoot integration) to orchestrate data pipelines, handle incoming user queries, and manage state.
*   **Large Language Model (LLM):** Connected to an advanced language model to process natural language queries and generate human-like, educational responses based on the localized wiki context.

---

## 🚀 Key Engineering Highlights

*   **Self-Hosted Infrastructure:** Orchestrated using containerized environments to ensure complete data privacy, low-latency processing, and high customization.
*   **Contextual Routing:** Implemented a structured workflow that intercepts user queries, references the local knowledge base, and constructs optimal prompts for the AI agent.
*   **Modular Design:** Built with completely independent layers, allowing any component (the wiki, the chat interface, or the LLM backend) to be upgraded or swapped without breaking the system.

---

## 📂 Repository Contents

*   `/config` - Core infrastructure configuration templates and deployment layouts.
*   `/workflows` - Exported automation logic and pipeline workflows.
*   `README.md` - Project overview and documentation.
