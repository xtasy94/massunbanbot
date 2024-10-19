# Mass Unban Discord Bot

#### Estimated Reading Time: 1-2 minutes

This Discord bot allows you to unban all banned users from your Discord server effortlessly. Follow the steps below to set it up on your own server.

## Setup Instructions

1. **Clone the Repository**  
   Begin by cloning the repository to your local machine:
   ```bash
   git clone https://github.com/xtasy94/massunbanbot.git
   ```

2. **Install Dependencies**  
   Navigate to the project directory and install the necessary dependencies:
   ```bash
   cd massunbanbot
   npm install
   ```

3. **Configure Your Bot**  
   Input your bot token and client ID in the `config.json` file. You can obtain your bot token and client ID from the [Discord Developer Portal](https://discord.com/developers/applications).

4. **Start the Bot**  
   Launch the bot with the following command:
   ```bash
   npm start
   ```

   If everything is set up correctly, you should see the following confirmation message:

   ![Confirmation Message](https://user-images.githubusercontent.com/106101646/234493131-e5572a18-d289-403f-949f-8104d7a31f17.png)

## Usage

1. **Invite the Bot to Your Server**  
   Ensure that the bot is added to your server.

2. **Initiate the Unban Process**  
   Use the following command to start unbanning all users:
   ```bash
   /unban-all
   ```

## Important Notes

- The bot requires the **`BAN_MEMBERS`** permission to successfully unban users.
- Please note that the bot will only unban users who have previously been banned; it does not affect users who have been kicked from the server.
