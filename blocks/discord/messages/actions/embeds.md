---
description: >-
  An Embed object is another component of Discord messages that can be used to
  present data with special formatting and structure.
---

# Embeds

## Create an embed with name

To create embeds is specially necesary to&#x20;

1. Inserting the block "Create an embed with name (name)"
2. Selecting a name to identify the embeds from the others in your workspace/proyect
3. Using the atleast "1" block from the "embed category"

<figure><img src="../../../../.gitbook/assets/screenshot (5) (1).png" alt=""><figcaption></figcaption></figure>

| Block                                                      | Function                                                                     | Output                                                             |
| ---------------------------------------------------------- | ---------------------------------------------------------------------------- | ------------------------------------------------------------------ |
| ![](<../../../../.gitbook/assets/screenshot (6) (1).png>)  | Set the color of an Embed through a Hexadecimal code or with a "color block" | ![](../../../../.gitbook/assets/imagen\_2022-10-13\_162110195.png) |
| ![](<../../../../.gitbook/assets/screenshot (10) (2).png>) | Set the "Author: **Name**" of an Embed through a "String" block              | ![](../../../../.gitbook/assets/imagen\_2022-10-13\_162247532.png) |
| ![](<../../../../.gitbook/assets/screenshot (13).png>)     | Set the "Author: **URL"** of an Embed through a "String" block               | ![](../../../../.gitbook/assets/imagen\_2022-10-13\_162349964.png) |
| ![](<../../../../.gitbook/assets/screenshot (16).png>)     | Set the "Author: **Profile URL"** of an Embed through a "String" block       | ![](../../../../.gitbook/assets/imagen\_2022-10-13\_162621132.png) |
| ![](<../../../../.gitbook/assets/screenshot (11).png>)     | Set the "Title: **Name"** of an Embed through a "String" block               | ![](../../../../.gitbook/assets/imagen\_2022-10-13\_162717620.png) |
| ![](<../../../../.gitbook/assets/screenshot (12).png>)     | Set the "Title: **URL"** of an Embed through a "String" block                | ![](../../../../.gitbook/assets/imagen\_2022-10-13\_162801092.png) |
| ![](<../../../../.gitbook/assets/screenshot (9).png>)      | Set the "Description**"** of an Embed through a "String" block               | ![](../../../../.gitbook/assets/imagen\_2022-10-13\_162919124.png) |
| ![](<../../../../.gitbook/assets/screenshot (17).png>)     | Set the "Thumbnail**"** of an Embed through a "String" block                 | ![](../../../../.gitbook/assets/imagen\_2022-10-13\_163004862.png) |
| ![](<../../../../.gitbook/assets/screenshot (25) (1).png>) | Set the "Image**"** of an Embed through a "String" block                     | ![](../../../../.gitbook/assets/imagen\_2022-10-15\_091935788.png) |
| ![](<../../../../.gitbook/assets/screenshot (23).png>)     | Set the "Title**"** and "Description" of a Field through a "String" block    | ![](../../../../.gitbook/assets/imagen\_2022-10-15\_092136802.png) |
| ![](<../../../../.gitbook/assets/screenshot (26).png>)     | Set the "Footer name**"** of an Embed through a "String" block               | ![](../../../../.gitbook/assets/imagen\_2022-10-15\_092941986.png) |
| ![](<../../../../.gitbook/assets/screenshot (27).png>)     | Set the "Footer Icon**"** of an Embed through a "String" block               | ![](../../../../.gitbook/assets/imagen\_2022-10-15\_094622048.png) |

## Usage of "Send embed with name {}" block

### Embed

You need to insert the name of the embed/s you want to send, if you ant to send more than 1 embed, use ", " for each embed name; The name of each embed cant include space characters.

#### Example:

<figure><img src="../../../../.gitbook/assets/screenshot (34).png" alt=""><figcaption></figcaption></figure>

### Embed Message Content

An embed can include messages by inserting **"with message**" option

#### Example:

<figure><img src="../../../../.gitbook/assets/screenshot (36).png" alt=""><figcaption></figcaption></figure>

## How to send an embed?

To send an embed you need the block \[Send embed with name {embed/s} ]. Here are some ways to send embeds:

<figure><img src="../../../../.gitbook/assets/screenshot (30) (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../../.gitbook/assets/screenshot (31).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../../.gitbook/assets/screenshot (32).png" alt=""><figcaption></figcaption></figure>

## Example

| Input                                                      | Output                                                             |
| ---------------------------------------------------------- | ------------------------------------------------------------------ |
| ![](<../../../../.gitbook/assets/screenshot (37) (1).png>) | ![](../../../../.gitbook/assets/imagen\_2022-10-15\_103425904.png) |

{% hint style="warning" %}
## Limitations

There are a few limits to be aware of while planning your embeds due to the API's limitations. Here is a quick reference you can come back to:

* Embed titles are limited to 256 characters
* Embed descriptions are limited to 4096 characters
* There can be up to 25 fields
* A field's name is limited to 256 characters and its value to 1024 characters
* The footer text is limited to 2048 characters
* The author name is limited to 256 characters
* The sum of all characters from all embed structures in a message must not exceed 6000 characters
* Ten embeds can be sent per message
{% endhint %}
