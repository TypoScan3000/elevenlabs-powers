---
name: "speech-to-text"
displayName: "ElevenLabs Speech to Text"
description: "Transcribe audio and video with ElevenLabs Scribe v2, including realtime streaming, diarization, and timestamps."
keywords: ["elevenlabs", "speech-to-text", "transcription", "scribe", "realtime", "diarization", "subtitles", "timestamps"]
author: "ElevenLabs"
---

# ElevenLabs Speech to Text

## Overview

Use this power for batch and realtime transcription workflows, including subtitle generation, multi-speaker transcription, and timestamped transcript pipelines.

## Onboarding

Before using this power, confirm:

- `ELEVENLABS_API_KEY` is available in your environment.
- Internet access to `api.elevenlabs.io` is available.
- Your runtime is configured with the ElevenLabs SDK or cURL.

Setup details are in `steering/installation.md`.

## Available Steering Files

- `installation.md` - SDK install and setup guidance
- `transcription-options.md` - diarization, keyterms, language, timestamps
- `realtime-client-side.md` - browser/client realtime setup
- `realtime-server-side.md` - server realtime integration
- `realtime-commit-strategies.md` - manual vs VAD commit patterns
- `realtime-events.md` - event model and payload handling

## When to Load Steering Files

- Installing dependencies and baseline setup -> `installation.md`
- Improving transcript quality/settings -> `transcription-options.md`
- Building browser/client realtime UX -> `realtime-client-side.md`
- Building backend realtime pipeline -> `realtime-server-side.md`
- Choosing commit strategy -> `realtime-commit-strategies.md`
- Handling event stream parsing/state -> `realtime-events.md`

## Usage Notes

- Use `scribe_v2` for high-accuracy batch processing.
- Use `scribe_v2_realtime` for low-latency live transcription.
- Enable diarization for meetings and interviews.
- Request word-level timestamps when subtitle alignment is required.
