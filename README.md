# 🤖 AI Agents with LangChain – Complete Assignment

## 📌 Overview

This project demonstrates the implementation of **AI Agents using LangChain**, including:

* Built-in tools
* Custom tools & toolkits
* Tool binding & calling
* ReAct agents
* Mini AI Assistant project

---

# 🧩 PART 1 – Tools in AI Agents

## ✅ Task 1: Understanding Tools

### What is a tool in an AI Agent?

A tool is an external function or service that an AI agent can use to perform tasks beyond its internal knowledge.

### Why do agents need tools?

* Access real-time data
* Perform calculations
* Interact with external systems
* Automate workflows

### Chatbot vs Agent

| Feature     | Chatbot           | Agent              |
| ----------- | ----------------- | ------------------ |
| Capability  | Conversation only | Action + reasoning |
| Tools       | No                | Yes                |
| Flexibility | Low               | High               |

---

## ✅ Task 2: Built-in Tools in LangChain

Used tools:

* Calculator
* Wikipedia
* Web Search (Tavily)

Steps:

* Initialized tools
* Tested each tool
* Printed outputs

---

# 🛠️ PART 2 – Custom Tools & Toolkits

## ✅ Task 3: Custom Tool

Created:

* `company_policy_lookup`

Function:

* Returns company policy info based on query

---

## ✅ Task 4: Custom Toolkit

Toolkit includes:

* Policy lookup tool
* Employee database tool
* Date/time tool

Grouped tools into a toolkit for agent usage.

---

# 🔗 PART 3 – Tool Binding & Calling

## ✅ Task 5: Tool Binding

* Bound tools to LLM using LangChain
* Used `initialize_agent`
* Enabled automatic tool selection

---

## ✅ Task 6: Tool Calling Flow

Flow:
User Query → LLM → Tool Selection → Tool Execution → Final Answer

Tested:

* Single tool queries
* Multi-tool queries

---

# 🧠 PART 4 – ReAct Agent

## ✅ Task 7: ReAct Overview

ReAct = Reason + Act

Steps:

* Think
* Act
* Observe
* Answer

### Why ReAct is powerful

* Handles multi-step reasoning
* Dynamically uses tools
* Improves accuracy

---

## ✅ Task 8: Build ReAct Agent

* Created agent using ZERO_SHOT_REACT_DESCRIPTION
* Attached tools
* Enabled reasoning + action loop

---

## ✅ Task 9: Testing ReAct Agent

Test cases:

* Factual questions (Wikipedia)
* Calculation questions
* Multi-step queries

Observed reasoning trace using verbose mode.

---

# 🚀 PART 5 – Mini Project: AI Agent Assistant

## ✅ Task 10: Agent Use Case

Built an AI assistant that:

* Answers questions
* Performs calculations
* Retrieves information
* Automatically selects tools

---

## ✅ Task 11: Observations & Insights

### Benefits of tool-augmented agents

* Real-time data access
* Accurate computations
* Handles complex tasks

### Challenges

* Slower execution
* Tool dependency
* Higher cost

### Chains vs Agents

* Chains: Fixed workflow
* Agents: Dynamic decisions

### Agents vs RAG

* Use Agents → for actions + reasoning
* Use RAG → for document-based Q&A

---

# 🏁 Conclusion

This project demonstrates how AI agents:

* Extend LLM capabilities using tools
* Perform real-world tasks
* Enable intelligent decision-making

LangChain provides a powerful framework to build scalable AI agents.

---

# ⚙️ Requirements

```bash
pip install langchain langchain-community openai wikipedia tavily-python
```

---

# 🔑 Environment Setup

```bash
export OPENAI_API_KEY="your_api_key"
```

---

# 👨‍💻 Author

Tejdeep Gardas
