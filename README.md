# AI Agent for Digital Financial Literacy – README

## Overview

This notebook (`AI_AGENT.ipynb`) demonstrates the creation and usage of AI Agents in IBM Watsonx's Agent Lab. It provides a guided walkthrough of:

- Authenticating with IBM Cloud using API keys
- Obtaining bearer tokens
- Setting up and using LangGraph agents with Watsonx foundation models
- Building and invoking a ReAct-based agent
- Handling tools and toolkits using LangChain and IBM Watsonx integrations

> ⚠️ **Note:** The notebook code is auto-generated from Agent Lab. Modifying or reordering code may result in execution issues.

---

## Technologies Used

- **Python 3.11**
- IBM Watsonx.ai
- LangGraph
- LangChain IBM integrations
- IBM Foundation Models
- REST API via `requests` module

---

## Goals

The notebook aims to:

- Authenticate with IBM Watsonx using an API key
- Retrieve bearer tokens from IBM IAM
- Create and configure a ReAct agent with tools
- Use LangGraph to build a conversational AI experience

---

## Setup Instructions

1. Clone this repository or download the notebook.
2. Install the required dependencies:
   ```bash
   pip install langchain_ibm ibm-watsonx-ai requests
