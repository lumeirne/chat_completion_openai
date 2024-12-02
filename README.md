# OpenAI Chat Completion Project

This project demonstrates how to interact with OpenAI's GPT-3.5 API to generate chat completions using Python. It utilizes the `openai` Python library and `dotenv` for securely loading environment variables.

## Prerequisites

Before running the project, ensure you have the following:

- Python 3.x
- [OpenAI API Key](https://platform.openai.com/signup) (You need to sign up on OpenAI's platform and generate an API key).
- The `openai`, `dotenv`, and `pandas` libraries installed.

## Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/lumeirne/chat_completion_openai.git
   ```
2. Install the required depencies.

3. Set up your environment variables:

Create a .env file in the root of the project directory.

Add your OpenAI API key to the .env file:

```makefile
OPENAI_API_KEY=your_openai_api_key_here
```
Make sure to replace your_openai_api_key_here with your actual OpenAI API key.

## Usage

1. Open the your_notebook.ipynb file in Jupyter Notebook or Jupyter Lab.
2. Run the cells to initiate a conversation with OpenAI's GPT-3.5 model.
3. Modify the user message in the notebook and see how the model responds to different inputs.

Note: Please refer the API docs if you encounter any errors.
