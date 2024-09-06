# Velatrix Minecraft plugin
![Latest version](https://img.shields.io/github/v/release/malejmarabu/Velatrix-MC-plugin?display_name=release&style=social&label=Latest%20version
)  ![Plugin downloads](https://img.shields.io/github/downloads/malejmarabu/Velatrix-MC-plugin/total?style=social&label=Total%20downloads)  
![Plugin stars](https://img.shields.io/github/stars/malejmarabu/Velatrix-MC-plugin?style=social)

Velatrix is a Spigot plugin designed to monitor your Minecraft server and track player activity in real-time. It provides users with a detailed overview of players and the ability to chat even when they are not playing.

## Features

- **Real-time server monitoring:** Monitor player information on the server.
- **Environmental information:** Monitor current weather/time/player count.
- **Notifications:** Notifications for specific events such as player deaths/joins/unjoins/advancements.
- **Live chat:** Chatting directly with players on the server.

## Installation

1. Download the latest version of Velatrix from [Releases](https://github.com/malejmarabu/Velatrix-MC-plugin/releases) on Github or from the [Velatrix](https://velatrix.xyz/download/) download page.
2. Place the `VelatrixMC-x.x.jar` file into the `plugins` folder of your server.
3. Restart your server to load the plugin.

## Setup

After installing Velatrix plugin and starting the server, the `config.yml` configuration file is generated in `plugins/VelatrixMC` directory. If the `config.yml` file has been generated, you're ready for the next steps in which you register your server to the system and configure it correctly, but if this doesn't happen, please visit our [Discord server](https://discord.gg/server).

### Step 1 - Go to Velatrix website
Go to [Server Registration](https://velatrix.xyz/create/) to continue with the following 5 steps.

### Step 2 - Tell us your server IP
Before entering the IP of your server, make sure your server is running! If it is, continue entering this IP in the box in step 1 and click Next. (**WARNING!! YOU HAVE ONLY A LIMITED NUMBER OF ATTEMPTS TO ENTER THE CORRECT IP AND THEN THE OPTION WILL BE BLOCKED FOR A WHILE!**)

### Step 3 - Name your server
Choose a name for your server and then enter it in the box in step 2 and click Next.

### Step 4 - Choose available URL for your server
Choose some free URL to access your page for your server and then enter it in the box in step 3 and continue by clicking Next.

### Step 5 - Specify owner
Then we will need to know the email address of the server owner as we may need to contact you. Enter the server owner's email in the box in step 4 and then click Create to get the server registration ID and token for your server.

### Step 6 - Complete registration
On step 5 it is important not to do anything prematurely, so don't click on anything or close the page wait for it and use the data on it next step.

### Step 7  - Edit `config.yml`
This is how your `config.yml` should look like before any modifications:

```yaml
monitor:
  serverID: "YOUR SERVER ID"
  APIToken: "YOUR TOKEN"

live_chat:
  enabled: false;
  port: 0
```
In this `config.yml`, replace the `APIToken` and `serverID` values with the values you obtained when you registered the server in step 5.
- `serverID` - 32 digit alphanumeric value (Server ID)
- `APIToken` - 16 digit alphanumeric value (Server token)

This is how your `config.yml` should look like after proper editing:

```yaml
monitor:
  serverID: "b2e4bfe78c7460fb34c365d6664ad692"
  APIToken: "uZofaldUzyhoVlik"

live_chat:
  enabled: false
  port: 0
```

### Step 8 - Enjoy
After all those brutally complicated steps, you can finally click Finish on step 5, which will take you to your server page, and if you want, you can additionally set up a live chat.

## License

This project is licensed under the Malejmarabu's Proprietary Software License - see the [LICENSE](./LICENSE) file for details.


------------

© Malejmarabu, 2024. All rights reserved.