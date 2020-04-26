---
title: Support Bot
description: 
published: true
date: 2020-04-26T03:15:36.278Z
tags: 
---

# Support Bot
A simple (ish) Discord™️ bot to manage support tickets to allow you and your team to provide better and quicker assistance to your community members.

**Go to the [Repo](https://github.com/ServerNode/Support-Bot) for more information**

## Commands
- `!help` - show help menu
- `!new` -  create a new ticket [`ticket`]
- `!close` - close a ticket
- `!add` - add a user to a ticket [`adduser`]
- `!remove` - remove a user from a ticket [`kick`]
- `!archive` - archives a ticket
- `!delete` - deletes an archived ticket

## Automations
The bot also runs on the background a schedule that locks a night channel for you from 6am till midnight.

The help menu provides an example for each command, along with usage (parameters info) and alias info.
An example command / template is provided if you want to create your own command (such as `!website` for example)
