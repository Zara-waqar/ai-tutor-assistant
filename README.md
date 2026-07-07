# AI Tutor Assistant

This project is an AI-powered tutor assistant built using **n8n** and **GPT-5 mini**. It is designed to answer both general knowledge questions and course-specific questions by choosing the appropriate information source.

For general questions, the assistant searches the web using Tavily Search. For questions related to course content, it retrieves information from structured Google Sheets based on a question ID provided by the user.

The project demonstrates how AI agents can use different tools depending on the user's request instead of relying on a single source of information.

---

## What this assistant can do

- Answer general knowledge questions using web search
- Retrieve course-specific questions from Google Sheets
- Identify which tool should be used based on the user's request
- Generate accurate responses using GPT-5 mini
- Combine AI reasoning with structured data retrieval

---

## Technologies Used

- n8n
- GPT-5 mini (OpenAI)
- Tavily Search API
- Google Sheets
- HTTP APIs

---

## How the workflow works

The assistant first analyzes the user's question.

If the question is general, it uses Tavily Search to find relevant information from the web before generating a response.

If the user requests a specific course question, the assistant asks for the question ID, retrieves the corresponding data from Google Sheets, and answers using that information.

This approach allows the assistant to use the right tool for the right task instead of treating every question the same.

---

## Why I built this project

I wanted to explore how AI agents can make decisions about which external tools to use based on user intent.

This project demonstrates tool routing, API integration, structured data retrieval, and AI reasoning within a single workflow.

---

## Skills Demonstrated

- AI Agent Development
- Workflow Automation
- Tool Routing
- Prompt Engineering
- API Integration
- Structured Data Retrieval
- Google Sheets Integration
- Web Search Integration
- LLM Applications

---

## Repository Contents

- `workflow.json` – Exported n8n workflow
- `README.md` – Project documentation
- `screenshots/` – Project screenshots
- `architecture/` – Workflow diagram *(coming soon)*

---

## Future Improvements

- Support for PDF knowledge bases
- Student conversation history
- Quiz generation
- Assignment assistance
- Multi-course support

---

## Author

**Zara Bukhari**

BS Software Engineering Student

Interested in AI Automation, LLM Applications, and Workflow Engineering.
