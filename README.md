# Nuelink

Plan, write and schedule your social media from Claude with your Nuelink account.

Ask Claude to draft a post and save it to Nuelink, schedule it for a specific time, or add it to a collection's posting queue. Nuelink publishes scheduled and queued posts to your connected channels, and supports Instagram, Facebook, TikTok, LinkedIn, X, Pinterest, YouTube, Threads, Bluesky, Google Business Profile, Telegram and Mastodon.

You can also check what's scheduled, see which posts went out or failed, and review likes, comments and other figures where each platform provides them. Set up feed automations that turn new blog articles, store products, videos or podcast episodes into drafts, and organize your collections and weekly posting times.

Before Claude schedules a post, it shows you the post, its channels and the timing, and asks you to confirm.

## Get started

You need a Nuelink account with connected social channels. The plugin works with the brands your account can access.

1. Add the plugin.
2. Connect Nuelink and sign in with your Nuelink account. In Claude chat and Cowork, use the plugin's **Connectors** tab. In Claude Code, run `/mcp`.
3. Try one of these:
   - What's scheduled to go out on my social channels this week?
   - Write a post announcing our new feature and save it as a draft in Nuelink.
   - How did my social posts perform last week?

## What's included

| Skill | What it does |
| --- | --- |
| `get-started` | Shows your brands, collections and channels without changing anything |
| `draft-first` | Writes a post and saves it as a draft, then checks that it saved |
| `schedule-approved` | Schedules or queues a post after you approve the details, then checks the result |
| `readback` | Reports drafts, queues, scheduled posts, and publishing results |
| `organize-safely` | Changes collections, channels, time slots and feed automations after you approve |

## What data it uses

The plugin contains instructions for Claude and runs no code on your computer. It connects to one service, Nuelink's MCP server at `https://mcp.nuelink.com/mcp`, and you sign in through OAuth, so Claude never sees your Nuelink password.

Through that connection, Claude sends the captions, media references, schedule times, collection changes and feed URLs you ask it to use. It reads your brands, collections, channels, posts, posting schedule, media library and publishing results. The plugin stores nothing itself. Nuelink handles this data as described in its [privacy policy](https://nuelink.com/privacy).

## What it doesn't do

The plugin doesn't connect new social accounts or manage plans and billing. Do those in your Nuelink account.

## Support

Get help at [help.nuelink.com](https://help.nuelink.com) or support@nuelink.com. Read the [MCP server documentation](https://docs.nuelink.com/mcp/) and the [terms of service](https://nuelink.com/terms).
