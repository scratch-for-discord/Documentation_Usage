# Security

## Tokens

{% hint style="danger" %}
Token = "password" to a bot

Not properly managing tokens can result in the bot's security being compromised

If you don't use [secrets](security.md#secrets), your token is usable by anyone being able to read your code

If you're still tempted to do not care, we advise you read [#negligence](security.md#negligence "mention")
{% endhint %}

For security concerns, we can use "[secrets](security.md#secrets)"

## Secrets

Secrets are [environment variables (`.env`)](https://en.wikipedia.org/wiki/Environment\_variable) with extra security measures to protect their values

### Conventions

* Environment variable names all in uppercase

### Storage

#### File

* [x] Create a `.env` file
* [x] Define environment variables and their value (one per line)\
  `ENVIRONMENT_VARIABLE_NAME = environment_variable_value`

#### [Repl.it](https://replit.com/)

{% hint style="danger" %}
If a bot's repository is on a [repl.it](https://replit.com/) free plan, your code is forced to be open-source

> If you don't use [secrets](security.md#secrets), your token is usable by anyone
{% endhint %}

<figure><img src="../.gitbook/assets/image (11).png" alt="Repl.it secrets"><figcaption><p>Repl.it secrets</p></figcaption></figure>

### Usage

This is the way you should connect to Discord:

<figure><img src="../.gitbook/assets/image (14).png" alt="S4D Block: Connect to Discord with token (process.env (environment variable) )"><figcaption><p>S4D Block: Connect to Discord with token (process.env (environment variable) )</p></figcaption></figure>

#### Exemple

If the token value is stored in a "`TOKEN`" variable inside of a "`process.env`" file, use:

> process.env (TOKEN)

{% hint style="success" %}
Congrats you have safely stored your token and are ready to continue coding!
{% endhint %}

## Possible Repercussions of Security Negligence <a href="#negligence" id="negligence"></a>

{% hint style="danger" %}
* Spy listening on the bot's reading data
  * Security negligence about sensitive user data is illegal in the EU
* Malicious usage of the bot
  * Nuke of every server the bot is in
  * Making the bot and the bot's account owner permanently banned from Discord
{% endhint %}
