# MeduLator AI  
### Multi-Specialist Analysis Engine for Medical Documents

MeduLation LLM is a lightweight AI-powered system for analyzing healthcare documents such as lab reports, discharge summaries, clinical notes, and medication records.

It is inspired by NotebookLM-style workflows but extends them into a **multi-specialist perspective reasoning simulation**, where different clinical viewpoints are generated to help users understand complex medical documents from multiple angles.

The system is designed for **education, research, and clinical document understanding support by users**, not for diagnosis or treatment.

---

## 🧠 Core Concept

MeduLation LLM introduces a **multi-specialist perspective reasoning approach** to medical document interpretation.

Instead of producing a single AI-generated answer, the system simulates how different medical roles would independently interpret the same clinical data:

- General Practitioner perspective  
- Internal Medicine perspective  
- Pharmacist perspective  
- Radiology interpretation perspective  
- Clinical Risk Analyst perspective  

Each perspective highlights different observations, concerns, and interpretations.

These are then combined into a structured, explainable overview of the patient documents.

### ⚠️ Important
This system is **not a diagnostic tool** and does not replace clinical judgment or healthcare professionals.

It is designed to support users' understanding of medical documents through structured AI-assisted reasoning.

---

## 🚀 Key Features

### 1. Multi-Specialist Perspective Analysis
AI agents simulate different clinical viewpoints:

- General Practitioner  
- Internal Medicine Specialist  
- Pharmacist  
- Radiologist  
- Clinical Risk Analyst  

Each agent independently analyzes uploaded documents and produces:
- Key observations  
- Potential concerns  
- Confidence levels  
- Source-linked evidence  

---

### 2. NotebookLM-Style Document Grounding
- Upload multiple medical documents (PDF, TXT)
- Enable/disable documents for analysis
- Every claim is traceable to:
  - Document name  
  - Page number  
  - Highlighted evidence in viewer  

No unsupported or untraceable medical statements are generated.

---

### 3. AI Chat Assistant
Users can ask natural language questions such as:

- “What does this diagnosis mean?”
- “Why is this medication prescribed?”
- “Are there any risks mentioned in the reports?”

The assistant:
- Provides grounded, cited responses  
- Links directly to source text in documents  

---

### 4. Symptom Relationship Graph
A dynamic visual graph showing relationships between:

- Diagnoses  
- Symptoms  
- Medications  
- Lab results  

Edges represent possible clinical relationships such as:
- Associated with  
- May contribute to  
- Requires monitoring  

---

### 5. Medical Timeline Generator
Automatically reconstructs a chronological patient journey:

- Diagnoses over time  
- Treatment changes  
- Lab result progression  
- Hospital visits  

Each event is linked to its source document.

---

### 6. Lifestyle Action Planner (Agentic Module)
Generates structured, educational lifestyle guidance based on extracted findings:

- Nutrition guidance  
- Physical activity suggestions  
- Sleep hygiene recommendations  
- Monitoring and follow-up tasks  

Each recommendation includes:
- Source reference  
- Reasoning explanation  
- Priority level  

---

### 8. Google Calendar Integration
Users can convert health-related actions into calendar events:

- Follow-up reminders  
- Lab test schedules  
- Monitoring tasks  

Features:
- One-click “Add to Calendar”  
- Google Calendar event generation via link-based API flow  
- Exportable care plan scheduling  


## ⚙️ Technical Stack

- Vanilla JavaScript (no backend)
- Tailwind CSS (UI framework)
- PDF.js (document parsing)
- Vis-Network (graph visualization)
- Markdown-it (chat rendering)
- Gemini 2.5 Flash API (LLM reasoning)
- LocalStorage (API key persistence)

---

## 🔐 API Key Handling

- Users provide their own Gemini API key
- Stored locally in browser only
- No backend or external server communication
- Fully client-side execution

---

## 🧪 Intended Use Cases

- Medical education and training  
- Clinical document interpretation practice  
- Healthcare AI UX research  
- Research prototyping for multi-agent systems  
- Patient record simulation studies  

---

## 🧠 Role of the System

MeduLation LLM is designed as a **decision-support and educational reasoning system**, not a clinical decision-maker.

It helps users:
- Understand complex medical documents  
- Compare multiple clinical perspectives  
- Identify uncertainties and missing information  
- Explore structured interpretations of health data  

It does NOT:
- Provide medical diagnoses  
- Recommend treatment plans  
- Replace healthcare professionals  

---

## 💡 Why This Project Is Novel

MeduLation LLM introduces a **multi-specialist perspective reasoning simulation layer** for medical document analysis.

Unlike traditional tools that generate a single summary, it:
- Separates interpretations by clinical role  
- Preserves disagreement and uncertainty  
- Maps clinical reasoning paths explicitly  
- Connects insights to source documents  

This makes medical document interpretation more transparent, explainable, and analytically structured.

---

## 📊 Feedback Requested from Medical Professionals

I am actively collecting feedback from healthcare practitioners regarding usability, interpretability, and clinical relevance.

👉 Feedback Form:  
**https://forms.gle/jbuN3bQsM8xTmRpE7**

I  especially welcome input on:
- Clinical usefulness of multi-specialist perspectives  
- Accuracy of document-grounded reasoning  
- Workflow integration potential  
- Safety and interpretability concerns  

---

## ⚠️ Safety & Disclaimer

MeduLation LLM is an educational and research simulation tool.

---

## 👩‍⚕️ Project Positioning

This system is positioned as:
- A **clinical reasoning simulation tool**
- A **multi-perspective medical document interpreter**
- A **research prototype for explainable healthcare AI interfaces**

---

## 📌 Future Improvements

- Expanded specialist roles (Oncology, Neurology, Pediatrics)
- Improved uncertainty scoring for clinical claims
- Better contradiction detection across long documents
- Enhanced explainability of AI reasoning chains

---

## 📄 License

For educational, academic, and demonstration purposes only.
