# ProactiveGPT

![logo](logo.png)
**Tired of asking ChatGPT by yourself? Let ChatGPT find you proactively!**

ProactiveGPT is a framework on top of OpenAI's ChatGPT models that brings a new level of interactivity to conversational AI by proactively engaging with the user. It can offer reminders, check-ins, tips, and inquiries to make the AI experience more dynamic and tailored to the user's needs. ProactiveGPT is particularly beneficial for coaching, personal assistance, and companionship use cases, providing support and guidance as needed. Written in Python, ProactiveGPT is a versatile and customizable solution for your AI needs.

## Features

- **Proactive Interaction**: ProactiveGPT goes beyond the traditional AI-user interaction by initiating conversations and offering timely assistance to users.
- **Reminders**: Keep track of important tasks and events with ProactiveGPT's customizable reminder options.
- **Check-ins**: Receive regular check-ins to stay on track with your goals and progress.
- **Tips**: Get relevant and personalized tips based on your preferences and objectives.
- **Inquiries**: ProactiveGPT can proactively ask questions to better understand your needs and provide targeted assistance.
- **Customization**: Tailor ProactiveGPT's behavior and responses to suit your unique requirements and preferences.

## Use Cases

- **Coaching**: ProactiveGPT can act as a virtual coach, offering guidance, encouragement, and feedback to help users achieve their goals.
- **Personal Assistance**: Keep track of appointments, manage tasks, and receive personalized support from your very own AI-powered assistant.
- **Companionship**: For those seeking companionship, ProactiveGPT can provide conversation, emotional support, and a friendly presence.

## Getting Started

To get started with ProactiveGPT, simply clone this repository and follow the installation instructions below.

```
git clone https://github.com/bcstyle/ProactiveGPT.git
```

## Prerequisites

Before you begin setting up this project, please ensure you have completed the following tasks:

### 1. Prepare OpenAI API Token

This application utilizes the OpenAI API to access its powerful language model capabilities. In order to use the OpenAI API, you will need to obtain an API token.

To get your OpenAI API token, follow these steps:

1. Go to the [OpenAI website](https://beta.openai.com/signup/) and sign up for an account if you haven't already.
2. Once you're logged in, navigate to the [API keys page](https://beta.openai.com/account/api-keys).
3. Generate a new API key by clicking on the "Create API Key" button.
4. Copy the API key and store it safely, as you will need it later during the setup process.

### 2. Create a Discord Bot and Get a Discord Bot Token

To integrate our application with Discord, you will need to create a Discord bot and obtain a bot token.

Follow these steps to create a Discord bot and get its token:

1. Go to the [Discord Developer Portal](https://discord.com/developers/applications) and log in.
2. Click on the "New Application" button in the top right corner and give your application a name.
3. Navigate to the "Bot" tab in the left sidebar and click on "Add Bot."
4. Confirm the action by clicking on "Yes, do it!" in the pop-up window.
5. In the "Bot" section, you will find the "Token" field. Click on "Copy" to save the bot token to your clipboard. Keep this token secure, as you will need it later during setup.

### 3. Get Your Discord User ID

In order to grant the bot the necessary permissions, you will need to provide your Discord User ID.

Follow these steps to obtain your Discord User ID:

1. Launch Discord and log in to your account.
2. Open your user settings by clicking on the gear icon near your username in the bottom left corner.
3. Navigate to the "Advanced" tab in the left sidebar.
4. Toggle the "Developer Mode" switch to enable it.
5. Close the user settings and return to your Discord server or any chat.
6. Right-click on your username in the member list or on one of your messages, and then click on "Copy ID" to save your User ID to your clipboard.

With these prerequisites completed, you are now ready to proceed with the installation and configuration of the project. In the next sections, you will learn how to set up the required environment variables and deploy the bot to your Discord server.

## Installation

1. Set up a Python virtual environment:

```
python -m venv venv
source venv/bin/activate
```

2. Install the required packages:
```
pip install -r requirements.txt
```

3. Run the ProactiveGPT application:
```
python proactive_gpt.py
```

4. Follow the questionnaire to customize your request.
An example with personal training coach is provided as default.

5. ProactiveGPT is running!
If you want to interact with it ad-hoc, you can use the !g discord command:
```
!g tell me how many exercise hours have you planned for me in total?
```

## Example Use Case
We provide an example of personal training coach use case in the default prompts. ProactiveGPT creates the entire training plan, with detailed time and activities. Then it will remind you with any planned exercise in real-time, per your requested cadence.

## Configuration

You can customize the behavior of ProactiveGPT by adjusting your answers to the questions at the beginning of program over shell. We will provide more customization options soon!

## Contributing

Contributions to the ProactiveGPT project are welcome! If you have any ideas for improvements or new features, please submit a pull request or open an issue.

## License

This project is licensed under the [MIT License](LICENSE).


