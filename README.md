# Bob - Slack Bot that uses OpenAI's ChatGPT to respond to messages

Bob is a Slack Bot that uses OpenAI's ChatGPT to respond to messages. The bot listens for mentions in Slack channels, retrieves the text following the mention, passes it to ChatGPT for processing, and posts the response back to the channel.

## Prerequisites
Python 3.7 or later
A Slack workspace with permissions to create a bot and install apps
An OpenAI API key

## Installation
Clone this repository to your local machine.
Install the required Python packages by running the command pip install -r requirements.txt in your terminal.
Create a .env file in the root directory of the project and add the following environment variables:

```makefile
SLACK_APP_TOKEN=<your Slack app token>
SLACK_BOT_TOKEN=<your Slack bot token>
OPENAI_API_KEY=<your OpenAI API key>
````

Start the bot by running the command python bob.py in your terminal.
Usage

To use Bob, mention the bot in a Slack channel by typing @bob followed by a message. The bot will respond with a message generated by ChatGPT.
