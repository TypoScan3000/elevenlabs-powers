---
name: "sound-effects"
displayName: "ElevenLabs Sound Effects"
description: "Generate sound effects from prompts with control over duration, looping, output format, and prompt influence."
keywords: ["elevenlabs", "sound-effects", "audio", "foley", "ambient", "looping", "sfx", "design"]
author: "ElevenLabs"
---

# ElevenLabs Sound Effects

## Overview

Use this power to generate non-speech audio such as ambient loops, UI sounds, impacts, and cinematic textures from text prompts.

## Onboarding

Before using this power, confirm:

- `ELEVENLABS_API_KEY` is available in your environment.
- Internet access to `api.elevenlabs.io` is available.
- Your runtime is configured with the ElevenLabs SDK or cURL.

Setup details are in `steering/installation.md`.

## Available Steering Files

- `installation.md` - SDK install and setup guidance

## When to Load Steering Files

- Installing SDKs or validating environment configuration -> `installation.md`

## Usage Notes

- Use specific prompts for higher quality outputs.
- Use `loop=true` for seamless ambient/background effects.
- Tune `prompt_influence` to trade off creative variation vs strict adherence.
- Choose output formats based on delivery target (web, DAW, telephony, realtime).
