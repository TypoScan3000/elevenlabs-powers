# ElevenLabs Kiro Power

One consolidated Kiro power for [ElevenLabs](https://elevenlabs.io) developer workflows.

This repository is a documentation-only power: a single root `POWER.md` plus capability-specific files in `steering/`. There is no `mcp.json` in this repo.

## Included Capabilities

- Text to speech
- Speech to text
- Conversational agents
- Sound effects
- Music

## How It Works In Kiro

1. Kiro loads the root `POWER.md` into the initial context window.
2. Kiro infers user intent from the prompt.
3. Kiro retrieves only the relevant files from `steering/`.

The installation and setup guidance now lives in one place: the root `POWER.md`. Capability-specific behavior stays in separate steering files so Kiro can retrieve a smaller, more targeted context set.

## Install In Kiro

Install this repository from:

- GitHub URL
- Local path

When installing from disk, select the repository root as the local power path.

## Configuration

Most workflows require:

```bash
export ELEVENLABS_API_KEY="your-api-key"
```

Get the key from [ElevenLabs API Keys](https://elevenlabs.io/app/settings/api-keys).

For JavaScript, use `@elevenlabs/elevenlabs-js`, not the legacy `elevenlabs` package.

## Testing

Use `TESTING.md` for the manual validation matrix covering setup and every routed capability in this power.

## License

MIT
