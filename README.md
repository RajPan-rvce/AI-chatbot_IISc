# Chatbot FAQ System

## Overview
This chatbot is designed to automate responses to frequently asked questions using Natural Language Processing (NLP) and fuzzy matching. It provides quick and accurate answers, improving customer support efficiency.

## Features
- **AI-Powered Response Matching**: Uses NLP techniques to understand and respond to queries.
- **Admin Panel for FAQ Management**: Update and add new questions easily.
- **Multi-Platform Deployment**: Can be integrated into websites, Telegram, or WhatsApp.
- **API Support**: Easily connect with other systems via REST API.

## Installation
### Prerequisites
- Python 3.8+
- Flask
- FuzzyWuzzy (for text matching)

### Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/chatbot-faq.git
   cd chatbot-faq
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the chatbot server:
   ```bash
   python app.py
   ```

## API Usage
Send a POST request to `/chat` with a JSON payload:
```json
{
  "message": "What are your working hours?"
}
```
Response:
```json
{
  "response": "Our working hours are Monday to Friday, 9 AM to 5 PM."
}
```

## Future Enhancements
- Improve NLP model with deep learning techniques.
- Expand multi-language support.
- Integrate chatbot with more messaging platforms.

## License
This project is licensed under the MIT License.
