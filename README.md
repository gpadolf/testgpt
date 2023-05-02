# ChitChatGPT Web Application

## Introduction

ChitChatGPT is a web application that allows users to interact with OpenAI's GPT-4 model through a simple interface. Users can submit text prompts and receive responses generated by the AI model. This project was created to address the limitations of GPT-4 and help users better manage their usage costs. The application displays the cost of each message for added convenience.

## Prerequisites

* Python 3.9

## :warning: Warning

Please ensure that you have set up billing limits on your OpenAI account before using this application. This will help prevent any unexpected charges due to potential issues with the application or API.

## Setup

1. Clone the repository and navigate to the project directory:

```
git clone https://github.com/yourusername/ChitChatGPT.git
cd ChitChatGPT
```


2. Install the required dependencies:

```
pip install -r requirements.txt
```


3. Set up your OpenAI API key:

```
export OPENAI_API_KEY="your-api-key"
```


4. Start the Flask web server:

```
python app.py
```


5. Open a web browser and navigate to `http://127.0.0.1:5000/` to interact with the ChitChatGPT web application.

## Usage

Enter your text prompt in the input field on the web page and click "Send" to submit the prompt to GPT-4. The AI-generated response will appear below your prompt, along with the cost of the message.

Enjoy chatting with GPT-4!