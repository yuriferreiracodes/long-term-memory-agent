# Long-Term Memory Agent

An AI agent that remembers customers between different chats.

Built with **LangGraph**, **OpenAI** and **SQLite**.

## How it works

- The customer tells the agent a preference or makes an order.
- The agent saves this information in a Store (SQLite).
- In a new chat, with no history, the agent searches the Store and gives the right answer.
- The search uses meaning (semantic search), not exact words.
- Each customer has their own data. Data from different customers does not mix.

## How to run

1. Open `long_term_memory_agent.ipynb` in Google Colab.
2. Add your `OPENAI_API_KEY` in the Colab secrets.
3. Run all cells.

## Context

This is a project from my MBA course "Agents, Multi-Agents and Interoperability".
