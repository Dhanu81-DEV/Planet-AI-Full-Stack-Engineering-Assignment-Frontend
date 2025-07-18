# 🌐 No-Code AI Workflow Builder – Frontend

This is the **React.js frontend** for the No-Code AI Workflow Builder. It provides a drag-and-drop canvas using React Flow to visually create AI workflows involving LLMs and document inputs.

---

## 📦 Tech Stack

- React.js
- React Flow
- Axios
- Tailwind CSS (optional)
- FastAPI backend (connected via REST API)

---

## 🚀 Features

- React flow nodes: User Query, LLM Model Selector, Output
- Visual workflow builder with zoom, pan, and connection arrows
- Upload PDF document for vector search
- Dropdown to select OpenAI or Gemini models
- Run button to trigger and display LLM responses

---

## 🛠️ Getting Started

### 🔧 Prerequisites

- Node.js ≥ 16.x
- Backend running at `http://localhost:8000`

---

## ▶️ Running the App

```bash
# Navigate to frontend directory
cd frontend

# Install dependencies
npm install

# Start development server
npm start
