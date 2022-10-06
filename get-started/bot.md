---
description: Learn how to create and manage your application
---

# Setting up bot

1. Start by going to [Discord developer portal](https://discord.com/developers/applications)
2. Click "New Application", if you don´t have one and set it´s name
3. On the left side you see a tab, in the General Information you can set your app name, description and icon
4. Now go to Bot and click "Add Bot", once you do so, your bot is created
5. Make sure to turn on all Privileged Gateway Intents - PRESENCE INTENT, SERVER MEMBERS INTENT & MESSAGE CONTENT INTENT
6. Click on Reset Token and Copy
7. In the next step [hosting.md](hosting.md "mention") you can see how to use the token.
8. You can now invite your bot in OAuth2 → URL Generator
9. In SCOPES select Bot and BOT PERMISSIONS should appear, there select the ones you want, you can select Administrator if you want it for testing (recommended on a new server)
10. Copy the URL and invite the bot to your server and your done!

{% hint style="danger" %}
Don´t share your bot token with anyone and use .env to keep it safe
{% endhint %}

> [https://discordjs.guide/preparations/setting-up-a-bot-application.html#creating-your-bot](https://discordjs.guide/preparations/setting-up-a-bot-application.html#creating-your-bot)
