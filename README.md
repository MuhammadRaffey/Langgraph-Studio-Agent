# LangGraph Project

This project uses LangGraph to create state graphs for various tasks. It includes dynamic breakpoints and an agent for performing arithmetic operations.

## Project Structure

- `agent.py`: Contains the implementation of an agent that performs arithmetic operations using LangChain and LangGraph.
- `dynamic_breakpoints.py`: Defines a state graph with dynamic breakpoints.
- `langgraph.json`: Configuration file for LangGraph.
- `.env`: Environment variables for the project.
- `.env.example`: Example environment variables file.
- `requirements.txt`: Python dependencies for the project.

## Setup

1. Clone the repository.

```sh
   git clone https://github.com/MuhammadRaffey/Langgraph-Studio-Agent
```

2. Create a virtual environment and activate it:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. Install the dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Create a `.env` file based on the `.env.example` and fill in the required values.

## Usage

```sh
langgraph up
```
