---
description: Application Creation and Management
---

# Bot Setup

## Application Creation

* [x] Go to the [Discord developer portal](https://discord.com/developers/applications)
*   [x] Click on "New Application" on the top right

    <figure><img src="../.gitbook/assets/image (12).png" alt="Discord Developer Portal﹣éNew Application&#x22; Button"><figcaption><p>Discord Developer Portal﹣éNew Application" Button</p></figcaption></figure>

It will then proceed to ask you a few questions\
Once finished:

*   [x] Click on "Create"

    <figure><img src="../.gitbook/assets/image (13).png" alt="Discord Developer Portal﹣&#x22;Create an Application&#x22; Modal"><figcaption><p>Discord Developer Portal﹣"Create an Application" Modal</p></figcaption></figure>

## Application Customization

On the left their is a sidebar which has a "General Information" option\
This is where you can customize the bot and add more information

<figure><img src="../.gitbook/assets/image (4).png" alt="Discord Developer Portal﹣&#x22;General Information&#x22; Menu"><figcaption><p>Discord Developer Portal﹣"General Information" Menu</p></figcaption></figure>

## Bot Creation

*   [x] Click on the far right "Add Bot" button

    <figure><img src="../.gitbook/assets/image (5).png" alt="Discord Developer Portal﹣&#x22;Add Bot&#x22; Button"><figcaption><p>Discord Developer Portal﹣"Add Bot" Button</p></figcaption></figure>

{% hint style="warning" %}
Scratch for Discord does only work with all Privileged Gateway Intents allowed:

* PRESENCE INTENT
* SERVER MEMBERS INTENT
* MESSAGE CONTENT INTENT
{% endhint %}

*   [x] Get the [token](../blocks/base.md#token)

    <figure><img src="../.gitbook/assets/image (6).png" alt="Discord Developer Portal﹣&#x22;Token&#x22; Page"><figcaption><p>Discord Developer Portal﹣"Token" Page</p></figcaption></figure>

{% hint style="warning" %}
It is impossible to get an already created [token](../blocks/base.md#token):\
If you have lost it, you need to reset it
{% endhint %}

{% hint style="info" %}
To know how to use the [token](../blocks/base.md#token), read[#token](../blocks/base.md#token "mention")
{% endhint %}

## Bot Invitation

*   [x] Click on OAuth2, then on "URL Generator"

    <figure><img src="../.gitbook/assets/image.png" alt="Discord Developer Portal﹣&#x22;OAuth2﹣URL Generator&#x22; Menu"><figcaption><p>Discord Developer Portal﹣"OAuth2﹣URL Generator" Menu</p></figcaption></figure>
* [x] Select Bot
* [x] Select the BOT PERMISSIONS you need _(recommandation: for a private bot, chose Administrator)_
* [x] Copy the URL
* [x] Invite the bot to the server you need

{% hint style="info" %}
Further information and official documentation:\
[https://discordjs.guide/preparations/setting-up-a-bot-application.html#creating-your-bot](https://discordjs.guide/preparations/setting-up-a-bot-application.html#creating-your-bot)
{% endhint %}
