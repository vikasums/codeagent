# Code Agent

A repository for code agent experiments and tutorials using Hugging Face's smolagents library.

## Description

This repository contains code and resources for exploring and learning about code agents. It demonstrates how to create and use code agents with Hugging Face API.

## Project Components

### code_agent.ipynb

The main Jupyter notebook demonstrates:

1. **Setting up the environment**:
   - Loading environment variables from `.env` file
   - Authenticating with Hugging Face using API key

2. **Creating custom tools**:
   - Implementing simple mathematical tools (sum_two_numbers, multiply_two_numbers)
   - Decorating functions with `@tool` for agent compatibility

3. **Initializing the Code Agent**:
   - Using HfApiModel with Llama-4-Scout model
   - Configuring the agent with tools and execution parameters

4. **Running the agent**:
   - Executing mathematical operations using the defined tools
   - Processing and displaying results

## Environment Setup

1. Create a Python 3.13 virtual environment:
   ```bash
   python3.13 -m venv venv
   source venv/bin/activate
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up environment variables:
   - Copy `.env.example` to `.env`
   - Add your Hugging Face API key


## Getting Started

Open the Jupyter notebook to explore the code agent implementation:

```bash
jupyter notebook code_agent.ipynb
```
