# 📄 Bulk Corporate Doc Automator

> An enterprise-grade, Python-based pipeline for bulk document proofreading, semantic validation, and automated formatting using LLMs.

![Project Demo](INSERT_YOUR_GIF_LINK_HERE)

## 🎯 The Corporate Bottleneck
Legal teams, HR departments, and administrative sectors waste countless hours manually reviewing thousands of internal documents, contracts, and reports. Surface-level grammar checkers fail to process files in bulk and lack contextual corporate tone adaptation.

## 💡 The Automation Solution
I engineered a **Batch Processing Workflow** that automatically scans input directories, processes multiple `.docx` files paragraph by paragraph using the **Groq API (Llama 3.3)**, and safely outputs fully refined documents into a dedicated delivery folder.

## 🛠️ Tech Stack & Architecture
- **Core Scripting:** Python (`os` library for directory traversal, `python-docx` for file manipulation)
- **AI Inference:** Groq API (High-speed NLP processing)
- **Architecture Pattern:** Batch Processing & Input/Output Pipeline Separation
- **Data Safety:** Zero overwriting. Original files remain untouched in the `input_docs` directory, while polished versions are securely generated in `output_docs`.

---
*Developed by Deivis Azeredo - AI Automation Specialist & Prompt Engineer*
