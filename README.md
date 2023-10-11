# Discord Chatbot with OpenAI GPT-3.5 Turbo

This application is a Discord chatbot that utilizes OpenAI's GPT-3.5 Turbo model to generate responses to messages in designated channels or when mentioned.

## Prerequisites

Before running the application, ensure you have the following:

- Node.js installed on your system.
- Discord bot token.
- OpenAI API key.

## Installation

1. Clone the repository or download the source code.
2. Navigate to the project directory.
3. Install the required dependencies by running:
   ```bash
   npm install
   ```

## Configuration

1. Create a `.env` file in the project root.
2. Add the following environment variables and provide appropriate values:
   ```plaintext
   TOKEN=YOUR_DISCORD_BOT_TOKEN
   API_KEY=YOUR_OPENAI_API_KEY
   ```

## Usage

Run the application using the following command:
```bash
node index.js
```

The bot will connect to Discord and start listening to messages in specified channels or when mentioned.

## Functionality

- The bot responds to messages using the GPT-3.5 Turbo model from OpenAI.
- It ignores messages that start with the specified prefix (`!` in this case).
- Messages are only processed in specific channels defined in the `CHANNELS` array.
- The bot replies with a generated response based on the received message.

## Contributing

Feel free to contribute to this project by creating issues or opening pull requests.
