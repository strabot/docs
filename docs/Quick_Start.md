# Quick Start

<img align="right" alt="Octocat" width="300px" src="_media/octogamer.png" />

Let's make a quick example of a Telegram bot using strabot. Let me present you our bot and friend called **Octogamer**: A specialist in games. You're gonna need to create a bot on Telegram, that is a pretty easy task using the @Botfather.

> If you don't know how to create, you can see the steps here: [Creating a new bot](https://core.telegram.org/bots#creating-a-new-bot)

Remember to get two important informations after create the bot:

* Token
* Username

We're gonna need these two soon.

## Setting up the Manager

Let's create our manager by using the following command:

```shell
npx @strabot/cli create manager --name octogamer-manager
```

Then we can get into the folder and execute the manager locally:

```shell
cd octomanager
npm run develop
```

After this, you can open the manager running by default on `http://localhost:1337`.

1. Create the first user
2. Open the **Content Manager** in the left menu
3. Open the **Telegram config** in the other menu
4. Set the **Active** as **TRUE**
5. Put the bot token in the **Token** field
6. Active 


## Setting up the Bot

```shell
npx @strabot/cli create bot --platform telegram --name octogamer-telegram
```
