# Graph2ML – Graph-based Classic Machine Learning Code Generator

**Graph2ML** is a beginner-friendly tool that lets you visually design classic machine learning workflows using a drag-and-drop graph interface, then automatically generates the corresponding Python ML code using a powerful LLM (Mistral AI).

---

## 🚀 Features

- 🎨 Intuitive frontend using **Next.js** and **React Flow**
- 🧠 Backend built with **Flask** and **Mistral AI** for code generation
- 🧪 Supports classic ML (e.g., train/test split, preprocessing, classifiers)
- 📜 Export generated code for Jupyter or script use
- 🔁 Real-time API response between frontend & backend

---

## 🛠️ Technologies Used

### Frontend:
- [Next.js](https://nextjs.org/)
- [React Flow](https://reactflow.dev/) – graph creation
- Axios – for API calls

### Backend:
- Flask – REST API
- Mistral AI – Model used for converting graphs to code
- JSON-based schema for graph structure

---

## 🧑‍💻 Getting Started

### 🔧 Backend Setup

```bash
cd backend
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirement.txt
python app.py
```

### 🌐 Frontend Setup
```bash
cd frontend
npm install
npm run dev
```


