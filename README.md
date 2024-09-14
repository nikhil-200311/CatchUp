# LLM-Based Newsletter Query Model

This repository contains a Language Learning Model (LLM) that processes up to **three newsletter URLs** as input and provides answers based on the content of those newsletters, along with the user query. The model parses the articles at the provided links, retrieves the relevant information, and responds intelligently to the user's questions.

## Features

- **Multi-newsletter Input**: The model accepts up to three URLs of newsletters.
- **Natural Language Query**: Users can input any question related to the content of the newsletters, and the model provides an accurate, context-aware response.
- **Text Processing**: Efficiently retrieves, processes, and analyzes the content of the newsletters to give concise and insightful answers.

## Technology Stack

- **Language Model**: A fine-tuned large language model (LLM) capable of understanding and analyzing newsletter articles.
- **Web Scraping**: Extracts data from the newsletter URLs to feed into the LLM for response generation.
- **API Integration**: Published as an API on the **On-Demand Platform** for easy integration with various applications.

## How to Use

### Input

1. Provide up to **three newsletter URLs** (formatted as strings).
2. Ask a **natural language query** related to the content of those newsletters.

### Example

```python
newsletters = [
    "https://example-newsletter-1.com",
    "https://example-newsletter-2.com",
    "https://example-newsletter-3.com"
]

query = "What are the key insights from these newsletters on the current financial market?"
    