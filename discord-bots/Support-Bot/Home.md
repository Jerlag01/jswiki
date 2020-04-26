---
title: Home
description: 
published: true
date: 2020-04-26T00:46:57.496Z
tags: 
---

## About
A simple (ish) Discord™️ bot to manage support tickets to allow you and your team to provide better and quicker assistance to your community members.

## Quick Start
[Download](https://github.com/ServerNode/Support-Bot/releases/tag/v1.1.2) the bot and extract or use `git clone https://github.com/ServerNode/Support-Bot.git`.
Follow setup instructions on the next page.

## Commands
- `!help` - show help menu
- `!new` -  create a new ticket [`ticket`]
- `!archive` -  archives a ticket
- `!delete` -  deletes an archived ticket
- `!close` - close a ticket
- `!add` - add a user to a ticket [`adduser`]
- `!remove` - remove a user from a ticket [`kick`]

The help menu provides an example for each command, along with usage (parameters info) and alias info.
An example command / template is provided if you want to create your own command (such as `!website` for example).

The bot can be configured to use either embeds or plain text.

Example of a new ticket:
![Image](https://i.imgur.com/ucqqTYG.png)

## Schedule
The Bot is equiped with a schedule that locks and unlocks a certain channel at a preconfigured time:
0:00 am: Unlocks the channel
6:00 am: Locks the channel

As you can determine this scheduler can be used to have a late-night channel.

Each server member is limited to one open ticket at a time (ticket channel name included part of their userID and discriminator to prevent the need to use a json file/database for user/channel information storage)

The bot also automatically pins the welcome message so it is easy for staff to nagivate to the start of the ticket.

[Getting Started](https://wiki.flanderscraft.be/en/discord-bots/Support-Bot/getting-started)