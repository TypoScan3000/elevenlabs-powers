---
name: "music"
displayName: "ElevenLabs Music"
description: "Generate music with ElevenLabs Music API for instrumental tracks, songs, background loops, and composition workflows."
keywords: ["elevenlabs", "music", "composition", "audio", "instrumental", "lyrics", "jingle", "soundtrack"]
author: "ElevenLabs"
---

# ElevenLabs Music

## Overview

Use this power to generate music from prompts, compose with structured plans, and choose between quick output and detailed metadata-rich generation.

## Onboarding

Before using this power, confirm:

- `ELEVENLABS_API_KEY` is available in your environment.
- Internet access to `api.elevenlabs.io` is available.
- Your runtime is configured with the ElevenLabs SDK or cURL.

Setup details are documented in `steering/installation.md`.

## Available Steering Files

- `installation.md` - SDK install and setup guidance
- `api_reference.md` - API methods, parameters, and usage patterns

## When to Load Steering Files

- Installing SDKs or validating local setup -> `installation.md`
- Selecting API methods or composing advanced requests -> `api_reference.md`

## Usage Notes

- Prefer `music.compose` for fast prompt-based output.
- Use `music.composition_plan.create` when you need section-level control.
- Use `music.compose_detailed` when you need output plus plan/metadata.
