<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/cartiqo/cartiqo/main/assets/banner-dark.svg">
  <img alt="CARTIQO. Designs it, builds it, ships it. I run what I build." src="https://raw.githubusercontent.com/cartiqo/cartiqo/main/assets/banner-light.svg">
</picture>

<br>

[![Studio](https://img.shields.io/badge/Studio-cartiqo.xyz-7C5CFF?style=flat-square&labelColor=111113)](https://cartiqo.xyz) [![GitHub](https://img.shields.io/badge/GitHub-CartiqoFramework-2A2D34?style=flat-square&labelColor=111113&logo=github&logoColor=white)](https://github.com/CartiqoFramework) [![Discord](https://img.shields.io/badge/Discord-Join%20the%20community-2A2D34?style=flat-square&labelColor=111113&logo=discord&logoColor=white)](https://discord.gg/A6b4bTTaeJ) [![Email](https://img.shields.io/badge/Email-hello%40cartiqo.xyz-2A2D34?style=flat-square&labelColor=111113)](mailto:hello@cartiqo.xyz)

</div>

## Hey, I'm Cartiqo

I make software in Denmark, and most of it ships under **CARTIQO**, the independent product studio I run. That covers my own products for Discord communities, a clothing label, and websites and bots for other businesses, shown working in full before anyone pays.

I design things and I build them, so nothing gets lost in a handover, and I keep running them after launch day.

This is my personal account. Studio code lives at [@CartiqoFramework](https://github.com/CartiqoFramework), and most of it stays private until it is worth someone else's time.

## What I'm building

| Project | What it is | Status |
| :-- | :-- | :-- |
| **[cartiqo.xyz](https://cartiqo.xyz)** | The studio's home. What CARTIQO makes, how a commission works, what it costs, and the writing. | Live |
| **[CARTIQO Tools](https://tools.cartiqo.app)** | Discord role icons, profile badges, icon packs and covers, designed in the browser at the sizes Discord actually shows them. There is a marketplace for what other people publish, and signing in with Discord is optional: it only turns on publishing. | Live |
| **CARTIQO Veyra** | Adaptive verification and security intelligence for Discord, built to stop abuse before it reaches a community. Every verification is scored across 16 signals, and every decision keeps the signals that produced it. | MVP |
| **Modyra** | Moderation for Discord, and nothing else. Every action becomes a numbered case, escalation follows a ladder you configure, and it never reads message content. Veyra's sibling. | Building |
| **CARTIQO Lists** | A directory for Discord bots and communities. Listings, voting and a public API. | Early |
| **CARTIQO Clothing** | A made-to-order clothing label. T-shirts, knitwear, outerwear and accessories, a short list in each, with no seasons and no drops. Opening at cartiqo.clothing and shipping worldwide. | Building |

## Work for other people

I build websites and custom Discord bots for other businesses. You send a brief, and if I take it on, you see the real thing working in full before any money moves. Like it and it is yours. If not, you owe nothing.

Live so far: [Walu_Cutzz](https://walucutzz.com), a booking site for a barbershop in Kolding where clients pick the cut and a time without a phone call or a DM.

Start a brief at [cartiqo.xyz/commission](https://cartiqo.xyz/commission).

## Open source

| Repository | What it does |
| :-- | :-- |
| [**discord-transcript**](https://github.com/CartiqoFramework/discord-transcript) | Self-contained HTML transcripts of Discord channels, rendered with Discord's own message components. On npm as [`@cartiqo/discord-transcript`](https://www.npmjs.com/package/@cartiqo/discord-transcript). TypeScript. |
| [**CTQCore**](https://github.com/CartiqoFramework/CTQCore) | FiveM core resource: connect queue and configuration, built on CTQBridge. Lua. |
| [**CTQBridge**](https://github.com/CartiqoFramework/CTQBridge) | Connects a FiveM server to a dashboard, so players can be kicked, banned and managed from a browser. QBCore, Qbox, ESX and standalone. Lua. |
| [**CTQui**](https://github.com/CartiqoFramework/CTQui) | A modern NUI kit for FiveM: notifications, text UI and progress bars. JavaScript. |

The three FiveM resources are early and untested on a production server. They are public so the work is readable, and each one says so.

## Writing

Notes from my own codebase, each one a real defect or a real decision, with the code that shipped.

- [Rate limit before you read the body, not after](https://cartiqo.xyz/blog/rate-limit-before-you-read-the-body)
- [Parsing the JSON is what breaks the webhook signature](https://cartiqo.xyz/blog/stripe-webhook-raw-body-signature)
- [An ARIA role is a promise, and a broken one is worse than none](https://cartiqo.xyz/blog/aria-roles-are-promises)
- [We build the site before we invoice for it](https://cartiqo.xyz/blog/we-build-it-before-you-pay)

All of it at [cartiqo.xyz/blog](https://cartiqo.xyz/blog).

## Stack

| Layer | What I use |
| :-- | :-- |
| Language | TypeScript everywhere, Lua for FiveM |
| Web | Next.js, React, Tailwind CSS, Vite |
| Bots and APIs | discord.js, Sapphire, Fastify |
| Data | Prisma, MySQL, Redis, Supabase |
| Payments and email | Stripe, Resend |
| Testing | Vitest, Playwright |
| Tooling and hosting | pnpm, Turborepo, Docker, GitHub Actions, Vercel, Cloudflare |

## Before CARTIQO

Mostly Discord bots.

- [**CoffeeBots**](https://github.com/CoffeeBotsXyz): a multi-purpose bot platform. Discontinued.
- [**ProjectBots**](https://github.com/ProjectDiscord/ProjectBots), formerly DiscoBots: a modular Discord bot framework. Discontinued.
- **Good Vibes Only**: a positivity-driven community [bot](https://github.com/gvobot/bot) and its [dashboard](https://github.com/gvobot/dashboard). Discontinued.
- **discord.js v14 systems**: [tickets](https://github.com/cartiqo/DJS-Ticket-System-v14), [help command](https://github.com/cartiqo/DJS-Help-Command-v14), [suggestions](https://github.com/cartiqo/DJS-Suggestion-System-v14), [server list](https://github.com/cartiqo/DJS-Simple-Server-List) and [templates](https://github.com/cartiqo/discordjs-v14-templates). Written in 2022 and left up for reference.

## Contact

Work, questions and everything else: [hello@cartiqo.xyz](mailto:hello@cartiqo.xyz). The community hangs out on [Discord](https://discord.gg/A6b4bTTaeJ), and help with the products is in the [support server](https://discord.gg/YTKp4MnN9Q).

I never ask for passwords, tokens or payment in a DM. If someone using the CARTIQO name does, report it to the address above. Security issues have their own route: read [SECURITY.md](https://github.com/CartiqoFramework/.github/blob/main/SECURITY.md) first.
