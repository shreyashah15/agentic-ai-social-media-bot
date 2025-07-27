# Agentic AI Telegram Bot for Real Estate Marketing 🏡🤖

A domain-specific Agentic AI and RAG-powered Telegram bot that generates branded social media visuals for real estate marketing. Built using OpenAI GPT-4, DALL·E, and n8n during my internship at Samyag.

## 🚀 Features
- Accepts prompts like "Make a Diwali post" or "Promote our 3BHK apartment"
- Applies a brand-specific memory: layout, colors, logos, bilingual (Gujarati-English)
- Generates image prompts via GPT-4 and creates visuals using DALL·E
- Sends the image directly back to the user on Telegram

## 🧠 Concepts Used
- Agentic AI behavior (goal + tool use)
- Retrieval-Augmented Generation (RAG)
- Prompt engineering and multimodal automation

## 🛠️ Tech Stack
- GPT-4 + DALL·E
- n8n
- Telegram Bot API
- JSON prompt memory

## 📸 Output Example
See `/media/` folder for screenshots.

## 📂 Project Structure
- `/prompt-memory`: Persistent system prompt used by the bot
- `/n8n-workflows`: Exported JSON workflow for the Telegram automation
- `/media`: Telegram bot output screenshots
