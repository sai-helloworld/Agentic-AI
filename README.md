🧠 Agentic-AI: Modular LangGraph Agent with Groq LLM Integration
Agentic-AI is a lightweight, modular framework for building agentic systems using LangGraph and Groq’s ultra-fast LLMs. It leverages LangChain's message abstraction and Groq's blazing inference speeds to create responsive, multi-turn agents with tool-using capabilities.

🚀 Features
LangGraph-powered agent flow: Define stateful, multi-node reasoning graphs with tool invocation and message tracking.
Groq LLM backend: Integrates GroqCloud’s openai/gpt-oss-20b for high-speed, low-latency inference.
Typed agent state: Uses TypedDict and Annotated to enforce structured message history.
ToolNode support: Easily plug in custom tools for retrieval, generation, or external API calls.
Environment-secured: .env support for managing API keys and secrets.

📦 Tech Stack
Python 3.10+
LangChain + LangGraph
GroqCloud API(llama, openai)
dotenv for environment management

🧩 Core Components
AgentState: Tracks conversation history using LangChain message types.

StateGraph: Defines agent flow logic with nodes and transitions.

ToolNode: Handles tool execution and response integration.


The Architecture Graph of the Email Agent:<img width="123" height="381" alt="image" src="https://github.com/user-attachments/assets/2272e0ce-a8c4-4309-b89a-1dd5763b2bfe" />

Project Images: \n 
<img width="1920" height="1080" alt="Screenshot 2025-09-06 115043" src="https://github.com/user-attachments/assets/2613885d-9ed9-4b6f-b76f-1ec13fe0d53b" />
<img width="1545" height="565" alt="Screenshot 2025-09-06 115006" src="https://github.com/user-attachments/assets/17284269-ff29-410b-8c48-2adee30c80e9" />
<--------------------------------------------------------------------------------------------------------------------------------------------------------->
<img width="1563" height="576" alt="Screenshot 2025-09-06 115020" src="https://github.com/user-attachments/assets/48b58447-b88c-4629-9b13-5c6faa206030" />
<--------------------------------------------------------------------------------------------------------------------------------------------------------->
<img width="1550" height="556" alt="Screenshot 2025-09-06 115032" src="https://github.com/user-attachments/assets/61ba9d67-3739-4071-82e3-c7a4e7df6b4a" />
<--------------------------------------------------------------------------------------------------------------------------------------------------------->
The Agent Created a File on it's own based on my Commands
<img width="1920" height="1080" alt="Screenshot 2025-09-06 114902" src="https://github.com/user-attachments/assets/eec56a92-837f-4929-827c-f99c9c5e0d31" />
 <img width="1920" height="1080" alt="Screenshot 2025-09-06 115043" src="https://github.com/user-attachments/assets/0d696cfb-87ba-4a76-b51a-15a09aa11e91" />
