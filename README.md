# Automated Lead Generation Tool

This is a Streamlit-based application designed to automate lead generation by scraping emails and actionable insights from URLs or Google search queries. The tool supports real-time scraping, enrichment, and interactive data management.

## Features

### 1. Scraping Pipeline

- Scrapes data from URLs or Google search queries.
- Extracts emails and relevant details.
- Enriches data with AI-generated insights using Groq API.

### 2. User-Friendly Dashboard

- **Interactive Table**: View, sort, filter, and select results using Ag-Grid.
- **Inline Actions**:
  - Delete or download individual entries.
- **Global Actions**:
  - Delete or download the entire table.

### 3. Pipeline Management

- **Run Pipeline**: Execute scraping and enrichment workflows.
- **Stop Pipeline**: Interrupt ongoing pipeline execution.

## Installation

### Prerequisites

- Python 3.8 or higher
- Internet connection

### Setup Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/jaswantsiddhu/lead-generation-automation.git
   cd Lead_scraper
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Create a `.env` file to securely store your Groq API Key:
   - In the root directory of the project, create a `.env` file.
   - Add the following line to the `.env` file:
     ```
     GROQ_API_KEY=your_api_key_here
     ```
4. Start the application:
   ```bash
   streamlit run dashboard.py
   ```




