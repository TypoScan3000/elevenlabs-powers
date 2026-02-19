# ElevenLabs Powers for Kiro

Kiro powers for [ElevenLabs](https://elevenlabs.io) developer workflows. Each power includes a `POWER.md` entry file and optional `steering/` guidance files.

This repository is organized as knowledge-base powers (no `mcp.json` files).

## Available Powers

| Power | Description |
|-------|-------------|
| [text-to-speech](./text-to-speech) | Generate natural speech with ElevenLabs voices |
| [speech-to-text](./speech-to-text) | Transcribe audio/video with Scribe v2, realtime, diarization, and timestamps |
| [agents](./agents) | Build and configure conversational voice AI agents |
| [sound-effects](./sound-effects) | Generate sound effects and ambient audio from text prompts |
| [music](./music) | Compose instrumental tracks and music from prompts |

## Use in Kiro

Install from:

- **GitHub URL**: add this repository in Kiro Powers
- **Local path**: add this repository folder from disk

Each power can be installed individually by selecting its folder (for example, `text-to-speech/`) as a local power path.

## Configuration

Most powers require an ElevenLabs API key:

```bash
export ELEVENLABS_API_KEY="your-api-key"
```

Get your API key from [ElevenLabs API Keys](https://elevenlabs.io/app/settings/api-keys).

## SDK Notes

Examples across powers use:

- **Python**: `pip install elevenlabs`
- **JavaScript/TypeScript**: `npm install @elevenlabs/elevenlabs-js`
- **cURL**: direct REST calls

For JavaScript, use `@elevenlabs/elevenlabs-js` (not the legacy `elevenlabs` package).

## License

MIT
