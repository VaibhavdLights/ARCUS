# ARCUS - Automated Research and Creation of Use Case Solutions

This repository contains a Multi-Agent System for generating AI and Generative AI (GenAI) use cases tailored for a specific company or industry. The system conducts market research, understands the industry landscape, and identifies relevant use cases and datasets to enhance operations and customer experiences through AI/ML solutions.

---

## Features

1. **Industry/Company Research Agent**:
   - Analyzes the industry segment and key offerings of the target company.
   - Identifies strategic focus areas like operations, supply chain, and customer experience.

2. **Market Standards & Use Case Generation Agent**:
   - Analyzes AI, ML, and automation trends within the company's sector.
   - Proposes actionable use cases leveraging GenAI, LLMs, and ML technologies.

3. **Resource Asset Collection Agent**:
   - Finds relevant datasets from platforms like Kaggle, HuggingFace, and GitHub for generated use cases.
   - Saves resource links in a structured file for future use.

4. **Bonus Features**:
   - Suggests GenAI solutions such as document search, automated report generation, and AI-powered chat systems.

---

## Getting Started

### Prerequisites

- Python 3.10+
- `requirements.txt` for dependencies
- API keys for GROQ, LangSmith, and Tavily services

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/arcus.git
   cd arcus
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up the `.env` file:
   Create a `.env` file in the root directory and add the following keys:
   ```env
   GROQ_API_KEY=<your_groq_api_key>
   LANGSMITH_API_KEY=<your_langsmith_api_key>
   TAVILY_API_KEY=<your_tavily_api_key>
   LANGSMITH_TRACING=true
   ```

4. Launch the notebook:
   ```bash
   jupyter notebook main.ipynb
   ```

---

## How It Works

1. **Input**: Provide the target company's name or industry.
2. **Execution**:
   - The system researches the company’s industry and identifies strategic areas.
   - It analyzes AI/ML trends and proposes relevant use cases.
   - Relevant datasets are identified and saved.
3. **Output**: A report containing use cases and dataset links.

---

## File Structure

- `main.ipynb`: The core implementation of the multi-agent system.
- `requirements.txt`: Python dependencies for the project.
- `.env`: Environment file to store API keys (to be created by the user).
- `resources/`: Folder containing the generated use cases and dataset links (if applicable).

---

## Example Use Cases

- **Retail Industry**:
  - AI-driven inventory management systems.
  - Generative AI for personalized customer recommendations.

- **Healthcare Industry**:
  - ML-powered patient diagnosis assistance.
  - Automated medical report generation.

---
