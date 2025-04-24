# 🤖 Agentic AI Insight System

A smart, interactive data analysis platform that allows users to upload datasets, ask business-related questions, and receive intelligent insights — all in one unified Streamlit app.

---

## 🧩 Problem Statement

In today’s data-driven world, businesses are inundated with massive volumes of structured and unstructured data. While data holds immense potential, **the real challenge lies in extracting meaningful insights** that can drive strategic decisions.

Many non-technical users struggle with:
- Interpreting raw data
- Creating meaningful visualizations
- Asking the right questions to guide decision-making
- Interacting with tools that require coding or technical expertise

This results in:
- Missed opportunities
- Delayed decisions
- Over-reliance on data science teams

There is a need for an **intelligent, accessible, and interactive platform** that bridges the gap between raw data and business intelligence — **without requiring technical skills**.

---

## 🎯 Objective

The goal of this project is to **develop a user-friendly AI-powered web application** that can:
- Accept various types of user-uploaded data (CSV, Excel, images, SQL)
- Understand user queries in natural language
- Analyze and visualize the data automatically
- Provide actionable business insights
- Allow follow-up questions to refine the analysis

By combining AI orchestration, natural language processing, and interactive visualization, this tool aims to **democratize data analytics** for business professionals and decision-makers.

---

## 🌟 Key Features

- **📁 Multi-format Upload**: Seamlessly upload CSV, Excel, image, or SQL files.
- **🧠 AI-Powered Analysis**: Powered by an intelligent agent using the Perplexity API for deep data understanding.
- **📊 Automa🏗️ Architecturetic Visualizations**: Generates numerical distributions, categorical overviews, and correlation heatmaps.
- **💬 Conversational Interface**: Enables natural-language interaction for deeper analysis.
- **🚀 One-click Insights**: No coding, no hassle — just upload and ask.

---

## 🏗️ Architecture
![Screenshot 2025-04-24 200617](https://github.com/user-attachments/assets/3b9ed04c-eaba-44f0-8b69-600b414ca8a5)


## 📂 Supported File Types

- `.csv` – Standard datasets
- `.xlsx` – Excel spreadsheets
- `.sql` – SQL database exports
- `.jpg`, `.jpeg`, `.png` – Visual data (e.g., charts, screenshots)

## 🧱 Project Structure

├── streamlit_app.py         # Main Streamlit frontend application
├── requirements.txt         # Python dependencies
├── README.md                # Project overview and documentation
└── AgentOrchestrator.py     # AI logic (not included, assumed custom)

## 🧠 How It Works

Upload your dataset (CSV, Excel, image, or SQL).

Describe your query (e.g., "Analyze revenue trends").

The app sends data and queries to an AI orchestrator (via the Perplexity API).

The AI returns:

Insightful text analysis

Data visualizations

A chat-based Q&A feature to dive deeper


