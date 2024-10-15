# Documentation for Velatrix plugin

In this documentation you will learn how to properly use and configure the Velatrix plugin.

- [**Server monitoring setup**](#server-monitoring-setup)
- [**Live setup**](#live-chat-setup)
- [**Plugin usage**](#plugin-usage)

---

## Server monitoring setup

After installing Velatrix plugin and starting the server, the `config.yml` configuration file is generated in `plugins/VelatrixMC` directory. If the `config.yml` file has been generated, you're ready for the next steps in which you register your server to the system and configure it correctly, but if this doesn't happen, please visit our [Discord server](https://discord.gg/X6tH34vC5X).

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
  enabled: false
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

---

## Live chat setup

---

## Plugin usage