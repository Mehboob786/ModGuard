# Django Application README

Welcome to our Django application! This application provides endpoints to Check The Harassment Level of single messages and lists of messages Using AI. The ModGuard repository introduces a Django-based application designed to evaluate the harassment level of messages using AI technology from Anthropic. This innovative tool leverages advanced AI models to analyze text content, identifying potential harassment and enabling proactive moderation measures. By integrating Anthropic's AI, ModGuard aims to create safer online environments, facilitating real-time assessment and moderation of user interactions. This introduction sets the stage for exploring the application's capabilities, setup, and integration process, emphasizing its role in enhancing online communication safety through AI-driven content moderation.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
  - [Running the Application](#running-the-application)
  - [Accessing Endpoints](#accessing-endpoints)
- [Customization](#customization)
  - [Editing Functions](#editing-functions)
- [Contributing](#contributing)

## Installation

To use this application, follow these steps:

1. Clone the repository:

```
git clone https://github.com/Mehboob786/ModGuard.git
```

2. Install dependencies:

```
pip install -r requirements.txt
```
3. Create Environment Variables or API Keys

For handling API keys securely in your Django application, such as the ones you might use with Anthropic's AI technology for the ModGuard project, it's essential to use environment variables. This approach keeps sensitive information out of your codebase, making it safer and more secure, especially when your code is stored in version control systems. Here's how to design your .env file specifically for storing API keys:

.env File Structure
Your .env file should contain key-value pairs, where each key is the name of the environment variable and the value is the secret API key or token. For instance:
```
ANTHROPIC_API_KEY=your_anthropic_api_key_here
```

## Usage

### Running the Application

Navigate to the project directory and run the following command to start the Django development server:

```
python manage.py runserver
```

The development server will start running at http://127.0.0.1:8000/.

### Accessing Endpoints

Once the server is running, you can access the following endpoints:

- Single message: `http://127.0.0.1:8000/single_message/`
- Message list: `http://127.0.0.1:8000/message_list/`

## Customization

### Editing Functions

To edit the functions and customize the behavior of the application:

1. Navigate to the appropriate views file (`views.py`) in your Django app.
2. Open the file in a text editor.
3. Locate the functions you want to edit (e.g., `single_message`, `message_list`).
4. Modify the function logic according to your requirements.
5. Save the file.

After editing the functions, make sure to restart the Django development server for the changes to take effect.

## Contributing

If you'd like to contribute to this project, feel free to fork the repository and submit a pull request with your changes.
