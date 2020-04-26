---
title: Configuration
description: 
published: true
date: 2020-04-26T00:41:10.994Z
tags: 
---

### token
Your Discord bot application (see **[**Getting Started**](https://wiki.flanderscraft.be/discord-bots/Support-Bot/getting-started)**)

**DO NOT SHARE**


### prefix
**Default:** `!`

Characters before the actual command to prevent multiple bots reacting to the same message


### name
**Default:** `Support Bot`

Name of your bot - leave blank for none (this is not currently used)


### guildID
**Default:** -

The ID of the guild your bot will operate on.
**Enable developer mode in Discord** (go to settings, appearance) then right click on your server's logo and copy ID.


### supportRole
**Default:** -

The ID of your support team role. Must be mentionable.
Type `\@MySupportRole` to get the id. Only copy the numbers, not the stuff around it.


### ticketsCat
**Default:** -

The category that tickets will be created under.
Create a category, right click and copy ID.


### logChannel
**Default:** -

Channel to log stuff into. Not currently configurable to be disabled but you can mute it.
Right-click, copy ID.


### archiveCat
**Default:** -

Category to move tickets to that needs to be archived.
Right-click, copy ID.


### nightchannel
**Default:** -

Channel which is only allowed to be talked in at night.
Right-click, copy ID.


### colour
**Default:** `#009999`

A hex colour code to use on embeds (#000000), or leave blank for default grey.


### playing
**Default:** `with tickets (!help)`

The text that will appear after PLAYING / WATCHING / LISTENING


### activityType
**Default:** `PLAYING`

Can be any of the following: `PLAYING`, `WATCHING`, or `LISTENING`


### status
**Default:** `ONLINE`

Online status: `ONLINE`, `IDLE`, `DND`, or `INVISIBLE`


### useEmbeds
**Default:** `true`

Whether to embed messages or not
`true` / `false`


### logDMs
**Default:** `true`

**PRIVACY THING:** If true, any messages sent from a member to the bot will be logged in the log channel you previously defined.
`true` / `false`


### cooldown
**Default:** `3`

Prevents users from spamming commands - seconds to make them wait before reusing a command


### ticketImage
**Default:** `true`

Whether to send an image when a ticket is created.
You can change this image, just replace `image.png` with your own. 
`true` / `false`


### tagHereOnly
**Default:** `false`


Only mention staff that are online?
If false, `supportRole` will be mentioned when a ticket is created
`true` / `false`


### ticketText
**Default:** `Thank you for reaching out to our support team.\nA member of staff will come to assist you shortly. Please describe the issue in detail and explain what you have done to resolve the issue so far.\n\n*If you feel that the support you receive is inadequate, please feel free to submit a formal complaint to a senior member of staff.*`
The text sent when a ticket is opened


### debugLevel
**Default:** `0`

`0` = info/warn/error only   /   `1` = debug messages (a lot more information)