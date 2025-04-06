# **LangGraph Chatbot with Wikipedia and Arxiv Integration**

Demo Video Link :- https://drive.google.com/file/d/1Ouz7Mt3WKN3OGPIcwa7GgSeXVFyMoWGM/view?usp=sharing
Colab Code Link :- https://colab.research.google.com/drive/1PvxctSEMWOG4JMbnVd0n_GeSoDDQAoPe?usp=sharing

This project is a tool-augmented chatbot built using LangGraph and Groq's LLM. It can intelligently respond to user queries and fetch real-time information from Wikipedia and Arxiv.

---

## **1. Overview**
Explains the purpose of the project — building a conversational AI that utilizes external tools for fetching informative content and research papers.

---

## **2. Project Architecture**
Describes how the LangGraph system flows:
- User input is passed to a chatbot node.
- The chatbot either answers directly or routes to external tools.
- Wikipedia and Arxiv provide relevant content when needed.

---

## **3. Technologies Used**
Lists all frameworks and APIs used:
- LangGraph for state-based flow.
- LangChain for LLM and tool abstraction.
- Groq for hosting the LLM.
- Wikipedia and Arxiv APIs for tool integration.
- Google Colab for easy execution.

---

## **4. Installation**
Explains how to set up the environment by installing necessary libraries using pip in Google Colab.

---

## **5. How It Works**
Describes:
- How tools like Wikipedia and Arxiv are configured.
- How the chatbot interacts with them based on the query.
- How LangGraph handles the conversation and conditionally calls the tools.

---

## **6. Usage Examples**
Provides three scenarios:
- Greeting message and basic reply.
- Querying Wikipedia for common topics.
- Using Arxiv to summarize research papers like “Attention is All You Need”.

---

## **7. Folder Structure**
Breaks down what each file in the repository does (e.g., the main notebook and README).

---

## **8. Use Cases**
Mentions real-world applications like:
- Research assistants.
- Educational chatbots.
- Demo projects for LLM-based tool usage.
