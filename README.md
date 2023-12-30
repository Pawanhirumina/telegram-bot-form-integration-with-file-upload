# Telegram Bot Form Integration with File Upload

This simple HTML form allows users to submit messages and upload files directly to a Telegram bot. The integration is powered by JavaScript and the Telegram API.

## Getting Started

### Prerequisites

- A Telegram Bot: Create a new bot and obtain the bot token by talking to the [BotFather](https://core.telegram.org/bots#botfather).
- Chat ID: Start a chat with your bot, send a message, and retrieve your chat ID by visiting `https://api.telegram.org/bot<YOUR_BOT_TOKEN>/getUpdates`.

### Usage

1. **Clone or Download:**
   - Clone this repository or download the HTML file (`index.html`).
   ```bash
   https://github.com/Pawanhirumina/telegram-bot-form-integration-with-file-upload.git
   ```

2. **Edit HTML File:**
   - Open `index.html` in a text editor.

3. **Replace Bot Token and Chat ID:**
   - Replace 'YOUR_BOT_TOKEN' and 'YOUR_CHAT_ID' with your actual Telegram Bot token and chat ID.

4. **Save the HTML File:**
   - Save the changes to the HTML file.

5. **Open in Browser:**
   - Open the HTML file in a web browser.

6. **Fill out the Form:**
   - Fill in the name, email, message, and select a file to upload.

7. **Submit the Form:**
   - Click the "Submit" button.

8. **Check Telegram Bot:**
   - Check your Telegram bot for the received message and file.

## Notes

- The file upload feature uses the `sendDocument` method of the Telegram API.
- Ensure your bot has the necessary permissions to access files and receive messages.

## Contributing

Contributions are welcome. Feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

