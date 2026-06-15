# 📈 Best Stocks - Multi-Agent Stock Research System

Best Stocks is an AI-powered multi-agent stock analysis and research system built using CrewAI. The project leverages a team of specialized AI agents that collaborate to analyze financial data, evaluate market trends, research companies, and identify promising stock investment opportunities.

By combining agentic workflows with Large Language Models (LLMs), Best Stocks automates the research process and generates structured investment insights that can assist investors, analysts, and financial enthusiasts in making informed decisions.

---

## 🚀 Features

* Multi-agent stock research workflow
* Automated financial analysis
* Company and market trend evaluation
* Collaborative agent decision-making
* Structured investment reports
* Modular CrewAI architecture
* Easy customization through YAML configurations

---

## 🛠️ Tech Stack

* Python 3.10+
* CrewAI
* Gemini API (Google Generative AI)
* UV Package Manager
* YAML Configuration
* Agentic AI Workflows

---

## 📂 Project Structure

```text
best_stocks/
│
├── src/
│   └── best_stocks/
│       ├── config/
│       │   ├── agents.yaml
│       │   └── tasks.yaml
│       ├── crew.py
│       └── main.py
│
├── .env
├── pyproject.toml
├── README.md
└── report.md
```

---

## ⚙️ Prerequisites

Before running the project, make sure you have:

* Python >= 3.10 and < 3.14
* Git installed
* Gemini API Key

---

## 🔧 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/abhishekpoddar29/Best-Stock-Picker.git

cd best_stocks
```

### 2. Create a Virtual Environment

```bash
uv venv
```

Activate the environment:

#### Windows

```bash
.venv\Scripts\activate
```

#### Linux / macOS

```bash
source .venv/bin/activate
```

### 3. Install CrewAI

```bash
uv pip install crewai
```

### 4. Install Gemini Support

```bash
uv add "crewai[google-genai]"
```

### 5. Install Project Dependencies

```bash
uv sync
```

### 6. Configure Environment Variables

Create a `.env` file in the project root:

```env
GEMINI_API_KEY=your_api_key_here
```

---

## ▶️ Run the Project

Start the CrewAI workflow:

```bash
crewai run
```

The agents will collaborate to perform stock research and generate investment insights based on the configured tasks and workflows.

---

## 🧩 Customization

### Agents Configuration

Edit:

```text
src/best_stocks/config/agents.yaml
```

to define agent roles, goals, and capabilities.

### Tasks Configuration

Edit:

```text
src/best_stocks/config/tasks.yaml
```

to customize research and analysis tasks.

### Crew Logic

Edit:

```text
src/best_stocks/crew.py
```

to add tools, workflows, and agent orchestration logic.

### Application Entry Point

Edit:

```text
src/best_stocks/main.py
```

to customize inputs and execution behavior.

---

## 📊 Example Use Cases

* Long-term investment research
* Stock screening and ranking
* Market trend analysis
* Financial data summarization
* Company performance evaluation

---

## 🤝 Contributing

Contributions, improvements, and feature suggestions are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Open a Pull Request

---

## 📜 License

This project is intended for educational and research purposes.

---

### ⭐ If you found this project useful, consider giving the repository a star.
