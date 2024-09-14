# History Companion: Interactive Timelines and Historical Events

History Companion is a Streamlit-based web application that serves as an interactive AI-powered guide for exploring historical events, timelines, and their significance. This application uses various language models to provide engaging and informative responses to user queries about history.

## Features

- Interactive chat interface for asking questions about historical events and periods
- Support for multiple AI models, including OpenAI's GPT models and Ollama's local models
- Customizable focus on specific historical categories
- Dark/Light theme toggle
- Conversation saving and loading functionality
- Token usage tracking

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/lalomorales22/HistoryCompanion-Streamlit100.git
   cd history-companion
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Set up your OpenAI API key as an environment variable:
   ```
   export OPENAI_API_KEY='your-api-key-here'
   ```

4. (Optional) If you want to use Ollama models, make sure you have Ollama installed and running on your system.

## Usage

1. Run the Streamlit app:
   ```
   streamlit run history_companion.py
   ```

2. Open your web browser and navigate to the URL provided by Streamlit (usually `http://localhost:8501`).

3. Enter your name and start asking questions about history!

## Customization

- You can modify the `HISTORICAL_CATEGORIES` list in the code to add or remove historical periods and themes.
- The custom instructions for the AI can be adjusted in the sidebar of the application.

## Contributing

Contributions to improve History Companion are welcome! Please feel free to submit pull requests or open issues to discuss potential enhancements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
