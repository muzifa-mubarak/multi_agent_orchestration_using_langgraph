# multi_agent_orchestration_using_langgraph
A multi-agent AI system built using LangGraph and LangChain, where a Supervisor Agent intelligently orchestrates multiple specialized agents (Research, Search, Writing, Tools) to solve complex user queries using LLM-driven reasoning and tool execution.

This project demonstrates agent orchestration, ReAct reasoning, tool calling, and state-based workflows, similar to real-world AI automation systems.

## 🚀 Key Features

🤖 Supervisor-based agent orchestration

🔍 Web research using Tavily Search

🧩 ReAct agents with tool calling

🧠 Google Gemini LLM integration

💬 Message-based state management

🔁 Iterative reasoning with recursion limits

🛠️ Extensible tool architecture (Python REPL, Web Search, etc.)

## 🏗️ System Architecture
```
**User Query
    ↓
Supervisor Agent
    ↓
 ┌──────────────┐
 │ Research     │
 │ Agent        │
 └──────────────┘
        ↓
 ┌──────────────┐
 │ Search Agent │
 │ (Tavily)     │
 └──────────────┘
        ↓
Supervisor → Final Response
**
```
## 📈 Future Enhancements

Add memory persistence

Add document writer agent

Streamlit UI

Multi-tool reasoning (search + scrape + summarize)

Evaluation & logging
