University of Belgrade Chatbot (Backend Only)

This repository contains the backend implementation of a simple chatbot for the University of Belgrade. It is designed to answer commonly asked questions from prospective students using real data scraped from the university’s website. The project was built using Python and OpenAI’s GPT-3.5-turbo model.

Note: This is a backend-only project. It does not include a graphical user interface. It is intended as a practice exercise and a demonstration of basic conversational AI and web scraping integration.


⸻

📌 Purpose

I chose to build this chatbot for the University of Belgrade not just as a technical challenge, but as a small act of support and awareness for the student-led protests against corruption in my country. By making educational resources more accessible and visible through open-source tools like GitHub, I hope to contribute—however modestly—to the movement for transparency, accountability, and student empowerment in Serbia.
⸻

🔧 What the Chatbot Does
	•	Answers user questions in a conversational format
	•	Provides helpful information on:
	•	Degree programmes
	•	Admissions
	•	Tuition
	•	General university services
	•	Uses OpenAI’s GPT-3.5-turbo model to generate natural language responses
	•	Scrapes real data from the University of Belgrade website to keep answers grounded in actual content
	•	Operates via terminal input/output (no GUI)

⸻

🧠 How It Works (Step-by-Step)
	1.	Web Scraping
The script uses requests and BeautifulSoup to scrape degree programme and admissions info from the University of Belgrade website.
	2.	Conversation Initialization
The scraped information is added to the system prompt to provide the language model with context.
	3.	User Interaction Loop
A terminal-based loop captures user input and maintains a running conversation using structured message history (system, user, assistant roles).
	4.	GPT-3.5 Response Generation
OpenAI’s Chat API is called with the current conversation context to generate a helpful and coherent reply.
	5.	Output to Terminal
The assistant’s response is printed in the terminal and added to the conversation history for follow-up questions.

⸻
📦 Tech Stack
	•	Python 3
	•	OpenAI GPT-3.5-turbo
	•	BeautifulSoup4
	•	Requests

⸻
🚫 Limitations
	•	No GUI – this is a command-line interface only
	•	Limited to English responses
	•	Web scraping is basic and may break if the university website structure changes
	•	This is not an official chatbot by the University of Belgrade

⸻
📣 Final Note

This is a learning project that I chose to work on in my free time, as I’m about to begin a part-time student job at my university focused on creating chatbots using large language models (LLMs). I also wanted to combine this opportunity to learn with my personal passion for supporting student-led protests and promoting democracy in my home country.
