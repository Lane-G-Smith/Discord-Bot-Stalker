<h1 align="center">Discord-Bot-Stalker</h1>
<table align="center">
  <tr>
    <td align="center" height="108" width="108">
        <img     src=""
        width="60"
        height="60"
        />
        <br /><strong>Discord.js</strong>
    </td>
    <td align="center" height="108">
      <p align="center">A Discord bot that emulates an annoyingly obsessed stalker that can be set to stalk someone using their client id. Every time the victim comments on anything, the stalker will reply with over-the-top inappropriate adoration and affection. Uses GPT3.5-Turbo-0613.
      </p>
     </td>
   </tr>
 </table>

# Installation and deployment instructions

## !!This bot does NOT respond to DMs, it must be in a server with you!!

### Get the bot 'shell' from Discord. It's free, and it takes 5 minutes
```sh
https://discord.com/developers/applications
```
### Go to OpenAI and open an account
```sh
https://platform.openai.com/signup
```
### Install node.js
```sh
https://nodejs.org/en/
```
### Install git
```sh
https://git-scm.com/downloads
```
### Create a new folder and navigate to it in the terminal to set up git
```sh
git init
```
### Navigate to the new git folder in the terminal and clone this repository
```sh
https://github.com/Lane-G-Smith/Discord-Bot-Stalker.git
```
### Navigate to the Discord-Bot-Stalker folder and install dependencies
```sh
npm install
```
### Rename example_.env to .env
### Place your secret Discord bot token from the first step into the .env file
```sh
TOKEN=your_unique_Discord_bot_token_here
```
### Place your secret OpenAI API key from the second step into the .env file
```sh
OPENAI_API_KEY=your_unique_OpenAI_API_key_here
```
### Right-click the user in Discord, copy the User ID and paste it into line 36 of stalker.js where it says "USER ID"
```sh
OPENAI_API_KEY=your_unique_OpenAI_API_key_here
```
### To host the bot locally, open the project in the terminal and run node
```sh
node stalker.js
```
### To host the bot locally and keep it running in the background indefinitely, install PM2
```sh
npm install pm2 -g
```
### Run your bot locally using pm2 https://pm2.keymetrics.io/
```sh
pm2 start stalker.js
```
### Congratulations, your bot should now be live & confirmation should be logged in the terminal. Use your personal link from the Discord developer portal to invite your bot to a Discord server
```sh
https://discord.com/developers/applications
```
