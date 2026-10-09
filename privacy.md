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
| Account creation date | For the account-age check of [fake detection](/features/fraud-detection). |
| Join and leave times | To count regular and left invites. |
| Invite code used, inviter ID, source link and campaign | The core of invite tracking. |
| Fake/verified flags and the reasons for a flag | Fake detection and [verified invites](/features/verified-invites). |
| Number of messages per day | [Message counting](/features/message-counting). Only the number, never the text. |
| Bonus invites, reward roles granted | [Rewards](/features/rewards). |
| Giveaway entries and winners | [Giveaways](/features/giveaways). |
| Audit log entries | A record of actions in the server, see [logs](/features/logs). |

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

- A server's data is kept for as long as the bot is in that server.
- History is never deleted because of the plan, also not when Premium expires. The plan only limits how far back you can *view* it in the dashboard (30 days of statistics and logs and 7 days of audit log on Free, everything on Premium). Renewing Premium makes the full history visible again.
- A server's data is deleted **90 days** after the bot is removed from it (so your history survives a temporary kick), or earlier on request.

## Who can see it

Members of a server can see invite counts and leaderboards through commands. Admins with *Manage Server* can see the full member and audit logs for their server in the dashboard. We do not share data with third parties, apart from Discord (which provides it) and Stripe (for payments).

## Deleting your data

- **Server owners**: remove the bot from your server; all data is deleted after 90 days. For immediate deletion, ask in our support server or open an issue on GitHub.
- **Individual members**: ask for removal of your data from one or all servers through the same channels. We will confirm within 30 days.

## Changes

If this policy changes in a meaningful way, we will update the date at the top and mention it in the changelog.

## Contact

Questions: open an issue on [GitHub](https://github.com/Djorr/Invitetree/issues) or use the support server.
