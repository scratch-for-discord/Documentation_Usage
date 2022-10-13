# Safely Storing Tokens

{% hint style="danger" %}
Not properly storing tokens can result in your bot being compromised,  Please do not share tokens with anybody!
{% endhint %}

## ENV

\
We recommend you use environment variables to safely store tokens because env variables are only able to be accessed locally, they cannot be used globally. Depending on where you host some hosts like repl only the free versions are publicly accessible which means all your code is essentially open source free to anyone to take a look.

That poses a risk because with a token they can do anything. Tokens are keys - They validate that the owner is you and then allow you to control your bot. But when an outsider gains that token, they then can use it to there advantage.

## How to store my token?

<figure><img src="../.gitbook/assets/image (14).png" alt=""><figcaption></figcaption></figure>

Firstly you will need this block, this specifies the token variable you would like to process. So if my token was inside of token.env - then I would say process.env.token. Process.env <mark style="color:orange;">****</mark><mark style="color:orange;">** **</mark>_<mark style="color:orange;">**returns an object containing the user environment**</mark>_<mark style="color:orange;">**.**</mark>

Then depending on the environment you are running the bot, if it is locally you will create a file called token.env if repl then you would secrets. as stated below

<figure><img src="../.gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>

{% hint style="success" %}
Congrats you have safely stored your token and are ready to continue coding!
{% endhint %}
