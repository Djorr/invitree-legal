---
layout: default
title: Invitree – Privacy Policy
permalink: /privacy/
---


# Privacy policy

*Last updated: 10 October 2026*

This policy explains what the hosted Invitree bot and dashboard store, why, and how to get it removed. If you run Invitree yourself, you are responsible for your own instance.

> In short: Invitree stores Discord IDs and the facts it needs to count invites. It **never** stores the content of messages, and it never sells or shares data.


## What we store

### About members of servers that use Invitree

| Data | Why |
|---|---|
| Discord user ID, username and avatar | To show who invited whom. |
| Account creation date | For the account-age check of [fake detection](https://djorr.github.io/invitree-legal). |
| Join and leave times | To count regular and left invites. |
| Invite code used, inviter ID, source link and campaign | The core of invite tracking. |
| Fake/verified flags and the reasons for a flag | Fake detection and [verified invites](https://djorr.github.io/invitree-legal). |
| Number of messages per day | [Message counting](https://djorr.github.io/invitree-legal). Only the number, never the text. |
| Bonus invites, reward roles granted | [Rewards](https://djorr.github.io/invitree-legal). |
| Giveaway entries and winners | [Giveaways](https://djorr.github.io/invitree-legal). |
| Audit log entries | A record of actions in the server, see [logs](https://djorr.github.io/invitree-legal). |

### About servers

Server ID, name and icon, the settings you choose in the dashboard, and the plan (Free or Premium).

### About dashboard users

When you log in with Discord we receive your user ID, username, avatar and the list of servers you are in, to show which servers you can manage. We store a session so you stay logged in. We never see your password or email address.

### About Premium customers

Payments are handled by Stripe. We store the Stripe customer and subscription IDs and the Discord ID of the person who pays. We never see or store card details.

## What we do not store

- The content of messages.
- Direct messages to the bot.
- Voice activity.
- Data from servers that do not use Invitree.

## How long we keep it

- Member data is kept while the bot is in the server, so your history survives a temporary kick.
- When the bot has been removed from a server for **90 days**, that server's data is deleted.
- Audit log entries older than the plan's history (7 days on Free, 365 days on Premium) are deleted.
- Daily message counts older than 365 days are deleted.

## Who can see it

Members of a server can see invite counts and leaderboards through commands. Admins with *Manage Server* can see the full member and audit logs for their server in the dashboard. We do not share data with third parties, apart from Discord (which provides it) and Stripe (for payments).

## Deleting your data

- **Server owners**: remove the bot from your server; all data is deleted after 90 days. For immediate deletion, ask in our support server or open an issue on GitHub.
- **Individual members**: ask for removal of your data from one or all servers through the same channels. We will confirm within 30 days.

## Changes

If this policy changes in a meaningful way, we will update the date at the top and mention it in the changelog.

## Contact

Questions: open an issue on [GitHub](https://github.com/Djorr/Invitetree/issues) or use the support server.


---
*This document is also published at https://djorr.github.io/invitree-legal/privacy/*
