# Postman Text Summarizer

## Overview
The **Postman Text Summarizer** is a web-based application designed to generate concise summaries from input text using AI-driven natural language processing (NLP). It is hosted on Render and can be accessed [here](https://postmantextsummarizer.onrender.com/).

## Features
- Summarizes long texts into key points
- User-friendly web interface
- Fast and efficient text processing
- Hosted on Render for easy access

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express.js
- **AI Model**: NLP-based text summarization (e.g., OpenAI, Hugging Face models)
- **Hosting**: Render

## Installation & Usage
To run the application locally, follow these steps:

### Prerequisites
- Node.js installed on your system
- Postman (optional for API testing)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/postman-text-summarizer.git
   cd postman-text-summarizer
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the server:
   ```bash
   npm start
   ```
4. Open your browser and go to:
   ```
   http://localhost:3000
   ```

## API Endpoints
### 1. Summarize Text
**Endpoint:** `POST /summarize`

**Request Body:**
```json
{
  "text": "Your long text goes here"
}
```

**Response:**
```json
{
  "summary": "Generated summary here"
}
```

## Deployment
The application is deployed on Render. You can access it via [this link](https://postmantextsummarizer.onrender.com/).




---

### Author
Developed by   Ruthika

