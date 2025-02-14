

# Google AI Text Generator Chatbot

This is a simple chatbot application built using **Streamlit** and **Google's Gemini API** to generate text-based responses.

## Features
- User-friendly interface for text input and chat history.
- Utilizes Google's **Generative AI** (Gemini) for text generation.
- Keeps track of user and assistant messages in the chat session.
- Displays responses dynamically using Streamlit's UI components.

## Installation

### Prerequisites
Ensure you have **Python 3.8+** installed.

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/chatbot
   cd chatbot
   ```
2. Install required dependencies:
   ```bash
   pip install streamlit google-generativeai
   ```
3. Run the application:
   ```bash
   streamlit run ChatBot.py
   ```

## Usage
1. Enter your text in the chat input field.
2. The chatbot will generate a response using Google's **Gemini API**.
3. Messages are stored in session state to maintain chat history.

## Configuration
Update the API key in `ChatBot.py`:
```python
api="YOUR_GOOGLE_API_KEY"
```
Replace `YOUR_GOOGLE_API_KEY` with your valid Google API key.

## Dependencies
- **Streamlit**: For the web interface.
- **Google Generative AI (Gemini)**: For text generation.

## License
This project is licensed under the MIT License.



