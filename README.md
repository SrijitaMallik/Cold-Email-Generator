GenAI Cold Email Generator

This project demonstrates how Generative AI can be used to automate cold email generation for business outreach, job applications, and marketing campaigns. The application takes basic user inputs (such as target industry, recipient role, and purpose of email) and produces a professional, well-structured email draft.

🔥 Problem Statement

Writing cold emails is often:

Time-consuming

Repetitive

Prone to sounding generic or unprofessional

Many professionals struggle to create personalized emails that grab attention and lead to responses.

🚀 Solution

This project leverages Large Language Models (LLMs) to automatically generate personalized cold emails. By feeding structured prompts into a GenAI model, the system produces context-aware emails that are:

Polite and professional

Tailored to recipient details

Concise yet impactful

🎯 Features

Input: Recipient details (name, role, company, industry, purpose)

Output: Cold email draft customized to context

Multiple tone options (formal, semi-formal, persuasive, etc.)

Easily extensible for LinkedIn messages, cover letters, or outreach templates

🛠️ Tech Stack

To get started we first need to get an API_KEY from here: https://console.groq.com/keys. Inside app/.env update the value of GROQ_API_KEY with the API_KEY you created.

Python

LangChain – for LLM integration

OpenAI API (or other LLM provider)

Streamlit – simple and interactive UI
