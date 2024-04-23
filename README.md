
# Chatbot with LLama3

This is a simple chatbot application built using the LLama3 model from OpenAI. The chatbot is deployed using Flask and can be accessed via a web interface.

<o><img height="400" width="1000" src="https://github.com/rajveersinghcse/rajveersinghcse/blob/master/img/llama3.png" alt="llama"></p>

## Features

- Uses the LLama3 model from Langchain for natural language processing.
- Utilizes dotenv for managing environment variables.
- Implements a ChatPromptTemplate for defining user and system messages.
- Supports querying the chatbot with user input.
- Web-based interface for easy interaction.
- Uses Bootstrap for styling.

## Prerequisite

- You have to install [Ollama](https://ollama.com/download) in your system.
- After installing the Ollama you have to install llama3 by using this command

## Getting Started

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/rajveersinghcse/Llama3-Chatbot.git
   ```

2. Navigate to the project directory:

   ```bash
   cd llama3-chatbot
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. In `.env` file paste your Langchain API key.

3. Run this command:

   ```bash
   flask --app app.py run
   ```

5. Open your browser and go to `http://localhost:5000` to access the chatbot.

## Usage

- Enter your query in the input field and click "Submit."
- The chatbot will process your query and respond.

## Customization

You can customize the chatbot's behavior by modifying the `initialize_chatbot()` function in `app.py`. For example, you can change the prompts or adjust the LLama3 model settings.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- OpenAI for providing the LLama3 model.
- Bootstrap for the frontend styling.
