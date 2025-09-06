# PyCharm Misc Project

A collection of Jupyter notebooks demonstrating LangChain integration with Ollama for various AI applications including LLM experimentation, conversational memory management, and output parsing.

## Project Overview

This project contains three main Jupyter notebooks that explore different aspects of LangChain and Ollama integration:

- **llm.ipynb**: Basic LLM model experimentation and parameter configuration
- **memory.ipynb**: Conversational AI memory management and state preservation
- **parser.ipynb**: Output parsing and structured data generation

## Features

### LLM Model Experimentation (`llm.ipynb`)
- Basic Ollama LLM integration using the Llama 3.1 model
- Parameter configuration (temperature, max tokens, frequency penalty, etc.)
- Travel recommendation system with Korean language support
- Astronomy Q&A system with customizable parameters

### Memory Management (`memory.ipynb`)
- Stateless vs stateful conversation comparison
- In-memory chat history implementation
- Session-based conversation tracking
- Contextual astronomy expert chatbot with memory persistence

### Output Parsing (`parser.ipynb`)
- Comma-separated list output parsing
- JSON output parsing with Pydantic models
- Structured recipe generation
- Format instruction integration

## Requirements

- Python 3.x
- Jupyter Notebook
- LangChain
- Ollama with Llama 3.1 model
- Pydantic

## Installation

1. Clone this repository
2. Install required dependencies:
   ```bash
   pip install langchain langchain-ollama pydantic jupyter
   ```
3. Install and set up Ollama with the Llama 3.1 model:
   ```bash
   ollama pull llama3.1
   ```

## Usage

1. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

2. Open any of the notebook files:
   - `llm.ipynb` - For basic LLM experimentation
   - `memory.ipynb` - For memory management examples
   - `parser.ipynb` - For output parsing demonstrations

3. Run the cells sequentially to see the examples in action

## Key Concepts Demonstrated

### LLM Parameters
- **Temperature**: Controls output randomness and creativity
- **Max Tokens**: Limits response length
- **Frequency/Presence Penalty**: Reduces repetition and encourages diversity
- **Stop Sequences**: Defines stopping conditions for generation

### Memory Types
- **Stateless**: Each conversation starts fresh without context
- **Stateful**: Maintains conversation history across multiple interactions
- **Session-based**: Separate memory contexts for different conversation threads

### Output Formats
- **Comma-separated lists**: For structured list outputs
- **JSON objects**: For complex structured data with validation
- **Custom schemas**: Using Pydantic models for type safety

## Examples

The notebooks include practical examples such as:
- Korean travel recommendations
- Astronomy Q&A with memory
- Recipe generation with structured output
- Multi-session conversation management

## License

This project is for educational and demonstration purposes.