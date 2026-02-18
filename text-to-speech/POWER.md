---
name: "text-to-speech"
displayName: "ElevenLabs Text to Speech"
description: "Generate natural speech with ElevenLabs voices across multiple models, languages, and output formats."
keywords: ["elevenlabs", "text-to-speech", "tts", "voice", "audio", "streaming", "voice-settings", "multilingual"]
author: "ElevenLabs"
---

# ElevenLabs Text to Speech

## Overview

Use this power to synthesize voice audio from text for narration, product voiceovers, assistants, and realtime voice applications.

## Onboarding

Before using this power, confirm:

- `ELEVENLABS_API_KEY` is available in your environment.
- Internet access to `api.elevenlabs.io` is available.
- Your runtime is configured with the ElevenLabs SDK or cURL.

Setup details are in `steering/installation.md`.

## Available Steering Files

- `installation.md` - SDK install and setup guidance
- `streaming.md` - realtime/streamed synthesis patterns
- `voice-settings.md` - stability, similarity, style, and speaker boost

## When to Load Steering Files

- Installing dependencies and base setup -> `installation.md`
- Building low-latency or chunked playback -> `streaming.md`
- Tuning output quality and voice behavior -> `voice-settings.md`

## Usage Notes

- Choose model based on quality/latency requirements.
- Use voice settings to balance consistency vs expressiveness.
- Use request stitching (`previous_text` / `next_text`) for long-form generation.
- Match output format to target platform (web, telephony, processing pipeline).
