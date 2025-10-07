# LangChain Demo

A small demonstration of LangChain framework capabilities, showcasing various features including prompt templates, chains, agents, and memory management.

The goal is for people to understand what an ai agent is and not a langchain training.

## 📋 Overview

This repository contains a Jupyter notebook that demonstrates key LangChain concepts and implementations:

- **Basic LLM Integration**: Setting up and using OpenAI's language models
- **Prompt Templates**: Creating reusable prompt structures
- **Chains**: Building sequential operations with LLMChain and SequentialChain
- **Agents**: Implementing intelligent agents with tools like Wikipedia and math calculations
- **Memory**: Managing conversation context and history

## 🚀 Getting Started

### Prerequisites

- Python 3.12 or higher
- OpenAI API key
- Jupyter Notebook or JupyterLab

### Installation

1. Clone the repository:

```bash
git clone https://github.com/AdanMora/langchain-demo.git
cd langchain-demo
```

2. Create a virtual enviroment

```bash
python -m venv .venv
```

```bash
source .venv/bin/activate
```

3. Install the required dependencies on the virtual env:

```bash
pip install -r requirements.txt
```

4. Set up your OpenAI API key:
   - Replace `"your_openai_api_key_here"` in the notebook with your actual OpenAI API key
   - Alternatively, set the `OPENAI_API_KEY` environment variable

### Running the Demo with visual studio code

1. Install the jupyter notebook extention
2. Open the 'ai_agent.ipynb'
3. Select the virtual enviroment in the notebook
4. Run each cel and follow the notebook.

# Note: if visual studio pop up to install a ipykernel do it, is need it for the notebook extention

## 📚 What's Included

### Core Components Demonstrated

1. **LLM Setup**: Basic OpenAI integration with temperature configuration
2. **Prompt Engineering**: Template-based prompt creation for restaurant naming
3. **Chain Operations**:
   - Simple chains for single operations
   - Sequential chains for multi-step processes
4. **Agent Framework**: Wikipedia and math tool integration
5. **Memory Management**: Conversation buffer and context preservation

### Example Use Cases

- **Restaurant Name Generator**: Generate creative restaurant names based on cuisine type
- **Menu Item Suggestions**: Create menu items for generated restaurant names
- **Wikipedia Agent**: Query Wikipedia and perform mathematical calculations
- **Conversational AI**: Maintain context across multiple interactions

## ⚠️ Important Notes

- Make sure to secure your OpenAI API key and never commit it to version control
- The examples are for educational purposes and may need optimization for production use
- Some features may require additional setup depending on your environment
