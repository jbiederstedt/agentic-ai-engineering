# Agentic AI Engineering

This repository contains the complete collection of projects and labs from **[The Complete Agentic AI Engineering Course](https://www.udemy.com/course/the-complete-agentic-ai-engineering-course/)** by Ed Donner on Udemy.

The course provides comprehensive training in building autonomous AI agents using the latest frameworks and technologies in the field of agentic AI engineering.

## 📁 Project Structure

### 01-foundations/

**Week 1: AI Agent Foundations**

- Introduction to OpenAI API and basic agent concepts
- Setting up development environment with Python 3.12+
- Understanding message formats and API interactions
- Basic prompt engineering and agent communication patterns

### 02-openai-agents-sdk/

**Week 2: OpenAI Agents SDK**

- Building agents using OpenAI's official Agents SDK
- Understanding agent tools and capabilities
- Implementing trace logging and debugging
- Creating multi-step agent workflows

### 03-crewai/

**Week 3: CrewAI Multi-Agent Systems**

- Building collaborative multi-agent systems
- Agent role definition and task delegation
- Crew coordination and workflow management
- Real-world multi-agent applications

### 04-langgraph/

**Week 4: LangGraph State Machines**

- Building stateful agent workflows with LangGraph
- Understanding state management and transitions
- Creating complex agent interaction patterns
- Implementing memory and persistence

### 05-autogen/

**Week 5: Microsoft AutoGen**

- Building conversational AI agents with AutoGen
- Multi-agent conversations and coordination
- Tool integration and function calling
- Distributed agent systems

### 06-mcp/

**Week 6: Model Context Protocol (MCP)**

- Integrating external tools and services via MCP
- Browser automation and web scraping
- File system operations and data management
- Building production-ready agent systems

## 🛠️ Technologies Covered

- **OpenAI API** - Core LLM integration
- **OpenAI Agents SDK** - Official agent framework
- **CrewAI** - Multi-agent collaboration framework
- **LangGraph** - State machine and workflow management
- **Microsoft AutoGen** - Conversational AI framework
- **Model Context Protocol (MCP)** - Tool integration standard
- **Playwright** - Browser automation
- **SQLite** - Local data storage
- **Gradio** - Web interfaces
- **Flask** - Web applications

## 🚀 Getting Started

### Prerequisites

- Python 3.12 or higher
- OpenAI API key
- UV package manager (recommended)

### Installation

1. Clone the repository:

```bash
git clone <repository-url>
cd agentic-ai-engineering
```

2. Install dependencies using UV:

```bash
uv sync
```

3. Set up your environment variables:

```bash
cp .env.example .env
# Edit .env and add your OpenAI API key
```

4. Activate the virtual environment:

```bash
uv shell
```

### Running Projects

Each week's projects can be run independently. Navigate to the specific directory and follow the instructions in the README files or Jupyter notebooks.

For example, to run the CrewAI debate system:

```bash
cd 03-crewai/01-debate
crewai run
```

## 🔗 Links

- [Course on Udemy](https://www.udemy.com/course/the-complete-agentic-ai-engineering-course/)
- [Instructor's LinkedIn](https://www.linkedin.com/in/eddonner/)
- [OpenAI Agents SDK Documentation](https://openai.github.io/openai-agents-python/)
- [CrewAI Documentation](https://docs.crewai.com/)
- [LangGraph Documentation](https://langchain-ai.github.io/langgraph/)
- [AutoGen Documentation](https://microsoft.github.io/autogen/)
- [Model Context Protocol](https://modelcontextprotocol.io/)
