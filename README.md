# Discord Bot for GCP Compute Engine
> A Discord bot which uses the Google Cloud API to provision a Compute Engine instance.

### Story
---------
My friend and I, we love playing Minecraft. What we don't like is going through the painful process of starting a server via the GCP console. So, I went ahead and built this Discord bot to automate that process.

• Typing in `!server status` gives the current status of the server.

• Typing in `!server start` starts the GCP Compute Engine instance.

• Typing in `!server stop` stops the GCP Compute Engine instance.

### Enough talk, how do I host my own bot and start using it to satisfy my laziness?

1. Make sure you have Node.js installed. You can download it [here](https://nodejs.org)
2. Install [yarn](https://yarnpkg.com) [OPTIONAL]
3. Clone this repo using `git clone https://github.com/kashifulhaque/discord-bot-for-gcp.git` command.
4. Move into the repo directory using `cd discord-bot-for-gcp` command
5. Create a new Discord App via it's [Developer portal](https://discord.com/developers)
6. Make sure to enable the bot and copy it's token. DO NOT REVEAL THE TOKEN TO ANYONE.
7. Also generate the Bot invite link while you are there. [Tell me how](https://discordjs.guide/preparations/adding-your-bot-to-servers.html#bot-invite-links)
8. Rename `dummy-discord-config.json` to `discord-config.json` and open the file. Paste the token in the required place.
9. Visit the [GCP Auth Docs](https://cloud.google.com/docs/authentication/production?_ga=2.205580179.1089106346.1589480557-1074299793.1585422711#obtaining_and_providing_service_account_credentials_manually) and follow the steps there to generate a service account alognwith the Auth key. A JSON file will be downloaded containing all the keys and tokens required. AGAIN, DO NOT SHARE THIS WITH ANYONE.
10. Replace the `dummy-GCP_config.json` with the JSON file you downloaded.
11. Type in `npm install` or `yarn install` [If you have yarn installed] to get all the required dependencies.
12. Type in `npm start` or `yarn start` [If you have yarn installed] to start the Discord bot

> If you face any problems, feel free to create an Issue from the Issues tab. I will try to respond as early as possible.
