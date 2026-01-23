# AI AGENT For Data Analysis & Visalization

This project, is a Python project that demonstrates how to build a conversational AI agent capable of data analysis and visualization using LangGraph, LangChain, and modern data science libraries. The project provides both local and deployed chat interfaces, making it suitable for experimentation, prototyping, and integration into larger data-driven applications.

Key Features
Conversational AI Agent: Interact with an intelligent assistant that can answer questions, analyze data, and generate visualizations.
Data Analysis: Leverage Pandas and SQLAlchemy to query, process, and summarize data.
Visualization: Automatically generate charts and graphs using Plotly based on user queries.
Extensible Design: Modular codebase allows easy extension with new tools, prompts, or models.

Use Cases
Data Exploration: Chat with your data, ask for summaries, trends, or specific insights.
Automated Reporting: Generate visual reports and charts from raw data with natural language commands.
Prototyping AI Workflows: Quickly test and iterate on conversational data workflows before production deployment.
Educational Tool: Learn about conversational AI, LangChain, and data science integration in Python.

Project Structure:

scout — > Core agent logic, tools for data access and visualization, and prompt templates.

frontend —>  Scripts to run the chat agent locally (chat_local.py) or in a deployed environment (chat_deployed.py).

pyproject.toml —>  Project dependencies and configuration.

Dockerfile —>  Containerization support for deployment.

.env —>  Environment variables for configuration (e.g., API keys, server URLs).


Common `uv` COMMANDS for This Project
1. Create a Virtual Environment ->
uv venv 

2. Sync Dependencies -> 
uv sync

3. Install the Project in Editable Mode -> 
uv pip install --editable .

4. Run the Project with the Virtual Environment -> 
uv run python frontend/chat_local.py
