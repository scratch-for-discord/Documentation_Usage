---
description: Learn how to create and manage your application
---

# Setting up Bot

### How to Create a bot?

Start By going to the [Discord](https://discord.com/developers/applications) Developer Portal then at the top right  Click New Application.

<figure><img src="../.gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>

It will then proceed to ask you a few questions before getting started - Once finished hit Create to create the application for your discord bot!

<figure><img src="../.gitbook/assets/image (13).png" alt=""><figcaption></figcaption></figure>

On the left their is a side bar, and an option named General Information  - this is where you can customize the bot and add more info - once you have done that click bot

<figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>



You should see on the far right an Add Bot Button, be sure to click it.

<figure><img src="../.gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>

It will ask if you want to create a bot on that application click yes if you want to if now just click Nevermind.

{% hint style="warning" %}
Make sure to turn on all Privileged Gateway Intents - PRESENCE INTENT, SERVER MEMBERS INTENT & MESSAGE CONTENT INTENT
{% endhint %}

Now we need to get our token, due to safety reasons tokens have to be regenerated everytime you visit the developer dashboard. So you will need to click  the reset token button to get the token

<figure><img src="../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
Please visit [security.md](security.md "mention"), result in not safely storing them can lead to your bot being compromised!
{% endhint %}

## How to invite bot to server?

1. In SCOPES select Bot and BOT PERMISSIONS should appear, there select the ones you want, you can select Administrator if you want it for testing (recommended on a new server)
2. Copy the URL and invite the bot to your server and your done!



{% hint style="info" %}
For further information visit: [https://discordjs.guide/preparations/setting-up-a-bot-application.html#creating-your-bot](https://discordjs.guide/preparations/setting-up-a-bot-application.html#creating-your-bot)
{% endhint %}

