# Summary GPT Bot

An AI-powered text summarization Telegram bot that generates concise summaries of text, URLs, PDFs and YouTube videos.

- EN Bot: https://t.me/summarygptenbot

## Features

- Supports text
- Supports URLs
- Supports PDFs
- Supports YouTube videos (no support for YouTube Shorts)

## Usage

| Environment Variable | Description |
|----------------------|-------------|
| OPENAI_API_KEY       | API key for OpenAI GPT API (required) |
| OPENAI_MODEL         | Model to use for text summarization (default: gpt-3.5-turbo) |
| TELEGRAM_TOKEN       | Token for Telegram API (required) |
| TS_LANG              | Language of the text to be summarized (default: Taiwanese Mandarin) |


```sh
# install libraries
pip install -r requirements.txt

Build the Docker image: In the terminal, navigate to the project directory and run the following command to build the Docker image:

docker build -t telegram-bot .

This command will build the Docker image using the specified Dockerfile and requirements.txt.

Run the Docker container: Once the image is built, run the following command to start a Docker container:

docker run -d telegram-bot

This command will start a container based on the built image, and the Telegram bot will be up and running.

```
