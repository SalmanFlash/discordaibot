# Discord Bot Builder

> ### Build your own Discord bot with ease using our Discord Bot Builder

---
> **Important**
>
> #### 2023-04-12 Bing now supported
> #### 2023-03-27 Bard now supported
> #### 2023-08-02 Unofficial GPT-4 is currently down

### Chat

!image

# Setup

## Prerequisites

* Run ```pip3 install -r requirements.txt```

* **Rename the file `.env.example` to `.env`**

* Recommended python version `3.9` +
---
## Step 1: Create a Discord bot

1. Go to https://discord.com/developers/applications and create a new application
2. Build a Discord bot under the application
3. Get the bot token from the bot settings

   !image
4. Store the bot token in `.env` under the `DISCORD_BOT_TOKEN`

   <img height="190" width="390" alt="image" src="https://user-images.githubusercontent.com/89479282/222661803-a7537ca7-88ae-4e66-9bec-384f3e83e6bd.png">

5. Turn MESSAGE CONTENT INTENT `ON`

   !image

6. Invite your bot to your server via OAuth2 URL Generator

   !image
---
> **Note**
>
> In Step 2, you only need to complete the authentication process for the model you want to use (it's not necessary to complete all Step 2)
>
> Remember to modify `CHAT_MODEL` to the default model you want to use in `.env` file

## Step 2: Official API authentication

### Generate an OpenAI API key
1. Go to https://beta.openai.com/account/api-keys

2. Click Create new secret key

   !image

3. Store the secret key in `.env` under the `OPENAI_API_KEY` variable
