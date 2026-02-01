# Vigil

**Always watching. Always ready.**

A personal fork of [OpenClaw](https://github.com/openclaw/openclaw) configured as my AI assistant.

## What is Vigil?

Vigil is my personal AI assistant that runs locally and communicates via WhatsApp, iMessage, Signal, and other messaging channels. Built on OpenClaw, it has:

- Multi-channel messaging (WhatsApp, Telegram, iMessage, Discord, Signal, Slack)
- Persistent memory across sessions
- Full system access (files, shell, browser)
- Skills/plugins system
- Claude Opus 4.5 as the primary model

## The Name

*Vigil* - like a night vigil, keeping watch. Always vigilant.

## Setup

```bash
npm install
cp config.example.yaml config.yaml
# Edit config.yaml with your API keys and channel settings
npm run dev
```

## Custom Skills

- `usccb-readings.ts` - Daily readings + saint of the day
- `bomforge-monitor.ts` - Pipeline/alerts
- `intranet-bridge.ts` - Connect to local command center
- `pypipeline-trigger.ts` - File organization

## Upstream

This is a fork of [OpenClaw](https://github.com/openclaw/openclaw). To sync upstream:

```bash
git fetch upstream
git merge upstream/main
```

## License

MIT (inherited from OpenClaw)
