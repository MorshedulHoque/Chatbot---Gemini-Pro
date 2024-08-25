# Gemini LLM Chatbot Application

## Project Overview
This chatbot application is built using the Gemini LLM provided by Google. It integrates environmental variables and a Streamlit interface to interact with users. The chatbot not only responds to user queries in real-time but also maintains a history of the conversation, allowing for context-aware interactions in a session.

## Features

| Feature               | Description                                                              |
|-----------------------|--------------------------------------------------------------------------|
| Environment Variables | Manages sensitive data using Python's `dotenv` package.                  |
| Streamlit Interface   | Offers a user-friendly, web-based interface for real-time interactions.  |
| Chat History          | Maintains a session-based history of conversations for context retention.|
| Gemini LLM Integration| Leverages Google's Gemini LLM for dynamic and intelligent responses.     |

## How It Works
1. **Environment Setup**: Manages API keys and sensitive information securely.
2. **User Interface**: Utilizes Streamlit to create an engaging and responsive user interface.
3. **Conversation Management**: Stores and retrieves chat history to maintain context in conversations.

## Getting Started
Follow these steps to set up the environment and run the chatbot application.

### Prerequisites
- Python 3.8+
- Streamlit
- dotenv Python package

### Installation
1. Clone the repository:
```bash
git clone https://github.com/MorshedulHoque/Chatbot---Gemini-Pro.git
```
2. Install dependencies:
```bash
pip install -r requirement.txt
```
3. Obtain a Google API key for the Gemini Pro model and add it to the .env file:
```bash
echo GOOGLE_API_KEY=your_api_key_here > .env
```
4. Run the Streamlit application:
```bash
streamlit run app.py
```

## Usage
-Start the application and navigate to the local URL provided by Streamlit.
![benchmark](https://github.com/MorshedulHoque/Chatbot---Gemini-Pro/blob/main/images/Screenshot_1.png)
-Enter your query in the text input box and submit.
![benchmark](https://github.com/MorshedulHoque/Chatbot---Gemini-Pro/blob/main/images/Screenshot_2.png)
-View both your question and the Gemini's response displayed on the screen, with previous interactions saved in session state for context.
![benchmark](https://github.com/MorshedulHoque/Chatbot---Gemini-Pro/blob/main/images/Screenshot_3.png)
![benchmark](https://github.com/MorshedulHoque/Chatbot---Gemini-Pro/blob/main/images/Screenshot_4.png)



## Acknowledgments
-Google AI for the Gemini LLM.
-Streamlit for the framework used in web application development.

## Contributions
Contributions are welcome! Please fork the project, make changes, and submit a pull request for review.

## Contact
For any queries or suggestions, please contact asmmorshedulhoque@gmail.com.

## Version
This application is currently at version 1.0.
