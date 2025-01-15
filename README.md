# Reddit Bot for Automated Content Generation

## Description

This project is a Reddit bot that automatically generates and posts content to a specified subreddit using Groq AI for content generation and Reddit API for posting. The bot runs daily at a user-specified time and ensures a seamless Reddit posting experience. It also supports basic error handling and logging, and features content generation through Groq AI. Additionally, the bot can be configured to generate and post comments on existing posts as a bonus feature.

## Features

- **Daily Automated Posting**: The bot posts content to Reddit at a specified time every day.
- **Groq AI Content Generation**: The bot uses Groq AI to generate engaging content automatically.
- **Reddit Integration**: Seamless integration with Reddit API for posting content and interacting with subreddits.
- **Error Handling & Logging**: Basic error handling and logging to ensure smooth bot operation.
- **Optional Comment Generation**: A bonus feature for automatically commenting on existing posts.

## Requirements

- Python 3.x
- Reddit API credentials (Client ID, Client Secret, Username, Password, User Agent)
- Groq API key for content generation
- Libraries: `praw`, `requests`, `schedule`

## Installation

### Step 1: Clone the repository

       ```bash
      git clone https://github.com/yourusername/Reddit_Bot.git
      cd Reddit_Bot
      pip install -r requirements.txt
### Step 2: Set up Reddit API credentials:

Go to Reddit Developer Apps.
Create a new app and select "script" as the app type.
Take note of the following details:
- Client ID
- Client Secret
- Username
- Password
- User Agent

### Step 5: Set up Groq API credentials:

- Visit Groq AI's website.
- Sign up or log in to your account.
- Obtain your API key from the Groq API section in your account settings.

### Step 6: Configure the credentials in the bot.py file:
     ```bash
    Reddit API credentials
    REDDIT_CLIENT_ID = 'your_client_id'
    REDDIT_SECRET = 'your_client_secret'
    REDDIT_USER_AGENT = 'your_user_agent'
    REDDIT_USERNAME = 'your_username'
    REDDIT_PASSWORD = 'your_password'
    GROQ_API_KEY = 'your_groq_api_key'

### Usage:
- Run the bot
- Customize Posting Time
- Monitor the bot
