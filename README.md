# Gemini-Pro Chatbot

This is a Streamlit-based chatbot integrating Google's Gemini-Pro AI model for real-time user interaction.

## Features
- Chat with Google's Gemini-Pro AI
- Maintains chat history
- Simple and responsive UI using Streamlit

## Installation

1. **Clone the repository:**
   ```bash
   git clone <repo-url>
   cd <repo-folder>
   ```

2. **Create a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up API Key:**
   - Create a `.env` file in the project root
   - Add your Google API key:
     ```
     GOOGLE_API_KEY=your_api_key_here
     ```

## Usage

Run the Streamlit app with:
```bash
streamlit run app.py
```

Then open the displayed local URL in your browser.

## Requirements
- Python 3.x
- Streamlit
- Google Generative AI SDK
- Python-dotenv

## License
This project is open-source and available under the MIT License.
