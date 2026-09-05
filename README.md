# 🤖 Agent AI

Generative AI and Agentic AI learning project using Python, LangChain, LangGraph, RAG, and LLMs.

## 🛠️ Setup

### 1. Go to Project

```powershell
D:
cd Agent_AI
```

### 2. Check uv

```powershell
uv --version
```

### 3. Initialize Project

```powershell
uv init
```

### 4. Create Virtual Environment

```powershell
uv venv
```

### 5. Activate Virtual Environment

```powershell
.venv\Scripts\activate
```

You should see:

```text
(Agent_AI) PS D:\Agent_AI>
```

### 6. Install Dependencies

```powershell
uv add -r requirement.txt
```

If there is a package-name error, check `requirement.txt` for typos.

### 7. Install Jupyter Kernel

```powershell
uv add ipykernel
```

### 8. VS Code Extensions

Install:

* Python — Microsoft
* Jupyter — Microsoft

### 9. Jupyter Kernel

In VS Code:

```text
Select Kernel
→ Python Environments
→ .venv
```



It should show:

```text
D:\Agent_AI\.venv\Scripts\python.exe
```

## 🔐 Environment Variables

Create `.env`:

```env
OPENAI_API_KEY=your_key
GEMINI_API_KEY=your_key
GROQ_API_KEY=your_key
```

