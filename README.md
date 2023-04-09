# chat-pdf-locally

This interactive script uses OpenAI's GPT-3 API to answer questions about a PDF document. It breaks the PDF document into chunks of text and uses GPT-3 to generate answers to user questions.

Forked from the project: https://github.com/jsonsmth/GPT-chatwithpdf

## Requirements

* Python 3.X
* OpenAI API key (sign up at [openai.com](https://openai.com/))
* PyPDF2
* requests
* transformers

## Installation

1. Clone the repository.

2. Install the required dependencies by running `pip3 install -r requirements.txt` in the project directory.

3. Paste your OpenAI API key to [`./resources/api-key.txt`](./resources/api-key.txt) file. (Sign up for the key at [openai.com](https://openai.com/).)

## Usage

### Running the script

Run the script by using the command `python3 chat.py <URL>` or `python3 chat.py <PATH>` in the project directory.
- Replace the `<URL>` with the URL of the PDF document you want to analyze.
- Replace the `<PATH>` with the path to the PDF document from your PC.

### Asking questions

Once the script is running, you can ask questions about the PDF document. Type a question and press Enter. The script will use GPT-3 to generate an answer to your question based on the PDF document.

### Providing feedback

After the script generates an answer, you can provide feedback by using one of the following options:

* Press the Spacebar to bypass the feedback prompt.
* Press the Up arrow key (`^`) to indicate that the answer was correct.
* Press the Down arrow key (`v`) to indicate that the answer was incorrect.

If you indicate that the answer was incorrect, the script will prompt you to provide the correct information.

### Quitting the script

To quit the script, type `quit` or `q` and press Enter.

## Supported Platforms

This script should run on any platform that supports Python 3 and the required dependencies, including Windows, Mac, and Linux.

Note: This script was written with the assistance of ChatGPT, a language model trained by OpenAI.
