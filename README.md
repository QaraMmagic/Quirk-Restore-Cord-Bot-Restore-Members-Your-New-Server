<p align="center">
  <img src="https://user-images.githubusercontent.com/106811566/172005677-0d2ca2fa-3b59-4e12-8388-d475d49df1f7.png" alt="RenewalSync Logo">
</p>

<h1 align="center">RenewalSync</h1>
<p align="center">
  <img src="https://img.shields.io/github/v/release/mayudev/revcord?style=for-the-badge" alt="Release">
  <img src="https://img.shields.io/github/license/mayudev/revcord?style=for-the-badge" alt="License">
  <img src="https://img.shields.io/github/languages/top/mayudev/revcord?style=for-the-badge" alt="Languages">
</p>

<p align="center"><b>🌉 A Cord to Connect Your Revolt and Discord Servers</b></p>

## Command List

Instead of prefixes, Nessie uses Discord's new [Slash Commands](https://support.discord.com/hc/en-us/articles/1500000368501-Slash-Commands-FAQ) `/`
- `br`: map rotation for battle royale
- `arenas`: map rotation for arenas
- `control`: map rotation for control
- `about`: information hub of Nessie
- `help`: list of commands and how to use them
- `invite`: generates Nessie's invite link
- `updates`: shows the latest news and current update of Nessie

## Features

- Bridge messages between platforms
- Bridge attachments
- Bridge replies
- Bridge message edit and delete
- Bridge embeds
- Seamlessly display user information

## Setup

New: You can use [Docker](#using-docker) instead.

**Node v16.9+ is required!**

1. Clone this repository, install dependencies and build
   ```sh
   git clone https://github.com/mayudev/revcord
   cd revcord
   npm install
   npm run build
   ```
2. Create bot tokens for Discord and Revolt
3. Configure tokens in environment variables or .env file
4. Invite the bot to both Discord and Revolt servers
5. Start the bot using npm start

Using Docker
You need Docker and docker-compose installed.

1. Create a .env file with bot tokens
2. Use `touch revcord.sqlite` to create the database file
3. Run: `docker-compose up -d`

Configuration
Use commands (rc! prefix on Revolt, or slash commands on Discord) to configure and connect channels
Toggle bot message forwarding using rc!bots or /bots