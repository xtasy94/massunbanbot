# Mass Unban Discord Bot
#### Reading time: 1-2 minutes read.
#### This is a Discord bot that can unban all banned users from a Discord server. Follow the steps below to set up the bot on your own server.


## Setup
Clone this repository: 
```
git clone https://github.com/xtasy94/massunbanbot.git
```
Install dependencies: 
```
npm install
```
Input your bot token and client ID in [config.json](https://github.com/xtasy94/massunbanbot/blob/main/config.json). You can get your bot token and client ID from the [Discord Developer Portal](https://discord.com/developers/applications).

Start the bot: 
```
npm start
```
If you see this then you're good to go:

![177293437-416679e8-8745-41aa-bb12-3fd7356c5d9e](https://user-images.githubusercontent.com/106101646/234493131-e5572a18-d289-403f-949f-8104d7a31f17.png)


## Usage
Invite the bot to your server.

Use this command to start the unban process:

```
/unban-all
```

## Note
<li> The bot requires the `BAN_MEMBERS` permission to unban users. </li>

<li> The bot will only unban users who have been banned previously. It will not affect users who have been kicked from the server.</li>
