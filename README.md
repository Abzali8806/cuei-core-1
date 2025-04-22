**Cuei Core 🧠**<br>
Cuei Core is the engine behind Cuei — the brains that power the vibe coding experience.<br>

Inspired by the phrase "to give a cue", Cuei translates your intentions into automated workflows and code. While Cuei App provides the user interface, Cuei Core handles all the heavy lifting under the hood.<br><br>


**🔍 What is Cuei Core?**<br>
*Cuei Core is a backend service that:*<br>

- Interprets user prompts from Cuei App<br>
- Generates code (Python, LangChain, and custom integrations)<br>
- Orchestrates workflows and connects to third-party APIs<br>
- Handles prompt engineering, AI model interactions (like GPT), and logic sequencing<br>
- Outputs deployable workflows that integrate into real-world systems<br>
- Cuei Core operates as a standalone service in its own repository, built to integrate seamlessly with Cuei App.<br><br>


**🏗️ How It Works**<br>
1. Cuei App sends user input (the "cue") to Cuei Core.<br>
2. Cuei Core processes the input:<br>
3. Analyzes intent<br>
4. Uses prompt engineering to structure requests<br>
5. Interacts with LLMs (e.g., GPT-4)<br>
6. Generates code, logic flows, or integration steps<br>
7. Returns structured outputs (code, configurations) back to Cuei App for user review and deployment.<br><br>


**🧩 Key Components**<br> 
- Prompt Processing Engine Refines user inputs and transforms them into model-ready prompts.<br>
- Code Generation Module Generates Python, LangChain, and custom logic scripts for workflows.<br>
- Integration Layer Connects with third-party tools (Airtable, APIs, Webhooks) to build end-to-end automations.<br>
- Workflow Orchestrator Sequences generated logic into coherent, executable workflows.<br>


**💻 Tech Stack Python**<br>
- LangChain<br>
- OpenAI GPT models (or other LLMs)<br>
- Custom Integration Scripts<br>
- FastAPI (or your chosen framework) for handling API communication with Cuei App<br><br>


**🚀 Getting Started**<br>
*1. Clone the repo:*<br>
```
git clone https://github.com/your-org/cuei-core.git
cd cuei-core
```
<br>

*2. Set up your environment:*<br>
*Recommended: use a virtual environment*<br>

```
# Create virtual environment

python -m venv venv
```

<br>

```
# Activate your virutal environment

source venv/bin/activate  # Mac/Linux
```

<br>

*3. Install dependencies from requirements.txt*
```
# Install your dependencies

pip install -r requirements.txt
```

<br>

*3. Configure environment variables:*<br>
Create a .env file and add the following API keys.<br>
```
OPENAI_API_KEY= ""
LANGSMITH_TRACING= ""
LANGSMITH_ENDPOINT= ""
LANGSMITH_API_KEY= ""
LANGSMITH_PROJECT= ""
TAVILY_API_KEY = ""
```
<br>

- ***LINKS TO GET ALL THE API KEYS LISTED AT THE BOTTOM OF THIS FILE***

**🎯 The Mission**<br>
Cuei Core makes vibe coding possible — transforming ideas into real code and automated processes, without the need for manual programming.<br><br>

**📄 License**<br>
Cuei Core includes software developed by LangChain (https://github.com/langchain-ai/langchain), licensed under the MIT License.<br><br>


**Get API's from the following links**<br>
- https://platform.openai.com/api-keys<br>
- https://smith.langchain.com/ - Find all langsmith keys here.<br>
- https://tavily.com/ - This isn't really needed as of now but it's a useful search tool.
