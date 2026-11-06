# AI Telegram Employee 🤖

An AI-powered virtual employee developed using n8n and OpenAI GPT-5-mini to automate administrative tasks through Telegram conversations.

The assistant understands natural-language instructions and performs tasks such as scheduling Google Calendar events and sending emails through Gmail.

## Features

- **AI-Powered Assistant:** Understands and processes user instructions using OpenAI GPT-5-mini.
- **Meeting Scheduling:** Creates Google Calendar events based on natural-language requests.
- **Email Automation:** Sends emails through Gmail based on user instructions.
- **Conversational Memory:** Maintains context across conversations using Simple Memory.
- **Telegram Integration:** Receives user commands and sends automated responses through Telegram.

## Tech Stack

- n8n
- OpenAI GPT-5-mini
- Telegram Bot API
- Google Calendar API
- Gmail API
- AI Agent
- Simple Memory

## Workflow

1. Telegram Trigger receives a message.
2. AI Agent processes the user's request.
3. OpenAI GPT-5-mini interprets the instruction.
4. Simple Memory maintains conversational context.
5. Google Calendar and Gmail tools execute the requested tasks.
6. Telegram sends the response to the user.

## Example

**User Request:**

"Schedule a meeting today at 5 PM on Google Meet and email the invitation to example@gmail.com regarding the upcoming course session."

**Result:**

The assistant creates a calendar event, sends an email, and confirms the completed actions through Telegram.
