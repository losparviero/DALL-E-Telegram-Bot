# Summariser Telegram Bot

Summarise any long text in Telegram, powered by GPT!

<br>

### Brief Note

This uses the official ChatGPT API which is paid hence will require an API key from OpenAI. You'll be billed for usage accordingly. Check OpenAI's website for pricing.

<br>

### Install

1. Clone git repo.
2. Run ```npm i``` in project folder.
3. Rename .env.example to .env and provide bot token & OpenAI API key.

4. Run ```node bot``` to start the bot.

#### It's advisable to run the bot using PM2 or any startup manager for persistent execution.

<details>

<summary>
.env reference
</summary>

<br>

BOT_ADMIN refers to the channel/user ID for logging purposes.

</details>

<br>

### Uninstall

1. Use ```rm -rf```.

*Note:* If you're unfamiliar with this command, delete project folder from file explorer.

<br>

### Mechanism

The bot uses OpenAI's DALL-E model API.

<br>

### License

AGPL-3.0 - ©️ Zubin