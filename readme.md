# Healthcare Assistant Chatbot

## Overview
The **Healthcare Assistant Chatbot** is a simple AI-powered chatbot that provides assistance with healthcare-related queries. It leverages a pre-trained Hugging Face model for text generation and implements basic rule-based responses for common medical inquiries. The chatbot is deployed using **Streamlit**, allowing users to interact through a web interface.

## Features
- Provides general healthcare-related responses.
- Identifies keywords such as "symptom," "appointment," and "medication" for tailored responses.
- Uses **Hugging Face's distilgpt2 model** to generate conversational responses.
- Simple and interactive **Streamlit-based web UI**.

## Installation
### Prerequisites
Ensure you have **Python 3.7+** installed on your system.

### Steps to Install and Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/healthcare-chatbot.git
   cd healthcare-chatbot
   ```
2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the chatbot:
   ```bash
   streamlit run app.py
   ```
5. The chatbot will be accessible at `http://localhost:8501` in your web browser.

## Dependencies
- `streamlit`
- `transformers`
- `nltk`

You can install these manually using:
```bash
pip install streamlit transformers nltk
```

## Usage
1. Open the chatbot in your browser.
2. Enter a healthcare-related question in the input field.
3. Click the **Submit** button to receive a response.
4. If necessary, refine your query for better results.

## Example Interactions
- **User**: "I have a headache."
  
  **Healthcare Assistant**: "It seems like you're experiencing symptoms. Please consult a doctor for accurate advice."

- **User**: "Can you book an appointment?"
  
  **Healthcare Assistant**: "Would you like me to schedule an appointment with a doctor?"

## Limitations
- This chatbot does **not** replace professional medical advice.
- Responses are **AI-generated** and may not always be accurate.
- It does **not** store user conversations or maintain session history.

## Contributing
Feel free to contribute by submitting issues or creating pull requests.


## Live Demo
Check out the chatbot in action: [Healthcare Assistant Chatbot](https://chat-bot-8.streamlit.app/)



