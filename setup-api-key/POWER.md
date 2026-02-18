---
name: "setup-api-key"
displayName: "ElevenLabs API Key Setup"
description: "Guide users through creating, validating, and storing an ElevenLabs API key for development workflows."
keywords: ["elevenlabs", "api-key", "authentication", "setup", "env", "credentials", "configuration"]
author: "ElevenLabs"
---

# ElevenLabs API Key Setup

## Overview

Use this power when a user needs to configure ElevenLabs access, when requests fail with authentication errors, or when onboarding a new project.

## Onboarding

This power requires internet access to:

- `https://elevenlabs.io`
- `https://api.elevenlabs.io`

## Workflow

### Step 1: Ask user to create/copy a key

Send the user to:

- `https://elevenlabs.io/app/settings/api-keys`

Tell them to create a key if needed and copy it immediately after creation.

### Step 2: Validate key

Validate with:

```http
GET https://api.elevenlabs.io/v1/user
xi-api-key: <provided-key>
```

If validation fails, ask for a new key and retry.

### Step 3: Store key in project env

Persist as:

```bash
ELEVENLABS_API_KEY=<provided-key>
```

### Step 4: Confirm success

Tell the user the key is configured and remind them not to share or commit secrets.
