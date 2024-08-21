# SBot

An AI-powered chatbot application built using the Rasa framework.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

## Introduction
SBot is an AI-powered chatbot application that leverages the Rasa framework to engage in natural language conversations. This project aims to create a versatile and intelligent chatbot that can assist users with a variety of tasks, from answering questions to providing personalized recommendations.

## Features
- **Natural Language Understanding**: The chatbot can understand and respond to user inputs using natural language processing techniques.
- **Intent and Entity Recognition**: The chatbot can identify the user's intent and extract relevant entities from the conversation.
- **Contextual Dialogue Management**: The chatbot can maintain context throughout the conversation, allowing for more natural and coherent responses.
- **Multi-language Support**: The chatbot can be configured to support multiple languages, making it accessible to a broader audience.
- **Customizable Responses**: The chatbot's responses can be customized to match the desired personality and tone.

## Installation
To set up the `sbot` project, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/joshnewans/sbot.git
   ```

2. Change to the project directory:
   ```
   cd sbot
   ```

3. Create a virtual environment (optional, but recommended):
   ```
   python -m venv env
   source env/bin/activate
   ```

4. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

5. Train the Rasa model:
   ```
   rasa train
   ```

## Usage
To run the chatbot, use the following command:

```
rasa run -m models --enable-api --cors "*" --debug
```

This will start the chatbot server, which you can then interact with using the Rasa command-line interface or by integrating it into your own application.

## Deployment
The `sbot` project can be deployed to various platforms, such as cloud services or on-premise servers. The specific deployment process will depend on the target environment and the infrastructure requirements.

## Contributing
Contributions to the `sbot` project are welcome. If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).
