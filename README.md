# ChatGPT3.5Turbo

This is a simple chatbot that uses OpenAI's GPT-3.5-turbo language model to generate responses to user input.
## This is a clone of https://github.com/kydycode/chatgpt-3.5-turbo.git
## I have added a few more features to it
## Installation

1. Clone the repository: `git clone https://github.com/Wall-EEE/ChatGPT3.5Turbo.git`
2. pip install openai
3. Set up an OpenAI API key by following the instructions [here](https://platform.openai.com/account/api-keys)
4. Add your API key to the `YOUR_API_KEY` field in `.env`

## Usage

To start the chatbot, run `main.py` using Python 3:

    python main.py


The chatbot will prompt you to enter your input, and then it will generate a response using the GPT-3 model. The conversation history is stored in a list of dictionaries called `message_log`.

To end the chatbot, type "quit" at any time.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

* This chatbot was inspired by the [OpenAI GPT-3 Playground](https://beta.openai.com/playground/)
* The GPT-3 model is provided by [OpenAI](https://openai.com/)
