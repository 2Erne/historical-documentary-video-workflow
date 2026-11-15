# Narrated 3D-Style Historical Documentary Workflow

Create historically grounded documentaries with painterly 3D-style animation and synchronized narration.

## Requirements

- A browser-capable agent that follows [SYSTEM_PROMPT.md](SYSTEM_PROMPT.md).
- Access to [VideoExpress](https://app.videoexpress.ai/) and its available generation features. Sign in when prompted.
- Narration can be generated with a suitable VideoExpress feature if available, or supplied as an audio file. If neither is available, choose an accessible voice tool.

This repository contains browser automation instructions; it is not a standalone application. Available controls, generation lengths and account access may vary.

## Getting started

Give the agent a historical topic or script, duration (default 60 seconds, up to five minutes), aspect ratio (default 16:9), narration language and voice, and whether you want an on-camera presenter (default no). Ask it to read and follow `SYSTEM_PROMPT.md`.

The agent researches the topic, prepares narration and scene prompts, creates painterly 3D-style keyframes and animation, then aligns each scene with the narration in the timeline. It saves and exports when the required controls are available. It does not share or publish without your instruction.

## Audio and timing

The requested duration guides script planning. The actual narration duration determines the visual coverage. The agent keeps completed narration intact and trims only excess video at its endpoint. Presenter speech remains audible and documentary clip audio is muted beneath the narration. If narration is unavailable or the completed audio exceeds the duration limit, the agent reports the issue instead of claiming a completed film.

The visual style describes a generated animation aesthetic; it does not require creating actual 3D models. Review the result before publication.
