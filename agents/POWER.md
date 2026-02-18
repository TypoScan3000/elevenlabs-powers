---
name: "agents"
displayName: "ElevenLabs Agents"
description: "Build voice AI agents with ElevenLabs for conversational assistants, customer support, and realtime voice experiences."
keywords: ["elevenlabs", "agents", "voice", "assistant", "convai", "realtime", "twilio", "widget", "tools"]
author: "ElevenLabs"
---

# ElevenLabs Agents

## Overview

Use this power when building or updating ElevenLabs conversational agents, including web widgets, client tools, outbound calls, and full agent configuration workflows.

## Onboarding

Before using this power, confirm:

- `ELEVENLABS_API_KEY` is available in your environment.
- Internet access to `api.elevenlabs.io` is available.
- You have an SDK or CLI installed for your language/runtime.

Recommended setup details are in `steering/installation.md`.

## Quick Start

Use the ElevenLabs CLI for rapid project bootstrapping:

```bash
npm install -g @elevenlabs/cli
elevenlabs auth login
elevenlabs agents init
elevenlabs agents add "My Assistant" --template default
elevenlabs agents push
```

## Available Steering Files

- `installation.md` - SDK/CLI setup and migration notes
- `agent-configuration.md` - Full configuration and CRUD workflows
- `client-tools.md` - Webhook, client, and system tool patterns
- `widget-embedding.md` - Website embedding and customization
- `outbound-calls.md` - Twilio integration for outbound phone calls

## When to Load Steering Files

- Installing dependencies or setting up local environment -> `installation.md`
- Creating/updating prompts, turn-taking, models, voices, or behavior -> `agent-configuration.md`
- Adding function-like capabilities and integrations -> `client-tools.md`
- Embedding agent UI into web apps -> `widget-embedding.md`
- Implementing outbound phone call flows -> `outbound-calls.md`
