# AI Agents Exploration

A repository created to document the learning of AI agents made using langgraph

### Order of agents in increasing level of complexity

1. [Blog Writer Agent](./blog-writer-agent.ipynb)
2. [Blog Writer SEO Agent](./blog-writer-with-seo.ipynb)
3. [Weather agent with tool calling](./weather-agent.ipynb)

### Ideas

#### Multi-Step Decision Agent
* Design a decision tree with LangGraph where the agent asks follow-up questions before answering.
* Example: A restaurant recommendation bot that asks for cuisine preference before suggesting places.

#### Conversational Agent with Memory
* Implement memory in the agent using LangChain’s memory modules.
* Example: A customer service bot that remembers user preferences.


#### Multi-Agent Collaboration
* Create multiple agents that communicate with each other.
* Example: A research assistant with different agents—one for web search, one for summarization, and one for answering queries.


#### Task Execution Agent
* Implement an agent that takes commands and performs basic tasks.
* Example: A personal productivity bot that creates and manages to-do lists.


#### Tool-Using Agent
* Enable your agent to use APIs/tools like a weather API, calculator, or news scraper.
* Example: A travel planner bot that fetches flight and hotel data.

#### Autonomous Research Agent
* Create an agent that takes a topic, searches the web, summarizes key insights, and presents a report.

#### Multi-Agent Ecosystem
* Develop a system where multiple agents specialize in different tasks (e.g., research, writing, and validation).


**Disclaimer- Some of the examples don't really require the use of langgraph. These are just made for learning purpose**