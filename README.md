# Saudi Tourism Data Agent

The **Saudi Tourism Data Agent** is an AI-powered assistant that retrieves, processes, and summarizes Saudi tourism statistics and visa regulations. It integrates multiple data sources, such as official reports from the Saudi General Authority for Statistics and the Ministry of Tourism, to provide answers to user queries.

This project is developed as part of the AIxplain Agent Course.

---

## Features

- **Tourism Statistics Search**  
  Retrieves official tourism data and reports based on user queries (e.g., "Tourism", "Domestic Travel", "Visa Guidelines").

- **PDF Processing**  
  Extracts relevant information from PDF files using Docling for text extraction and indexing.

- **Visa Regulations Search**  
  Answers questions about visa policies using a pre-indexed Tourist Visa Regulations PDF.

- **Semantic Q&A**  
  Provides accurate answers with contextual summaries using Retrieval-Augmented Generation (RAG) techniques.

- **External Tool Integration (ToDo)**  
  Supports optional connections to tools like Google Sheets, Slack, or Vercel for data sharing and notifications.

---

## Setup and Configuration

### Prerequisites

- Python 3.8 or later
- Google Cloud account for OAuth 2.0 (optional, if using Google services)
- aiXplain account for API access

### Installation

Install required Python packages:
pip install -r requirements.txt


### Example Usage 

response = agent.query("Get Tourism Statistics related number of female employees out of total employees in tourism activities")
print(response)


