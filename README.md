# PitchKit

AI pitch generator for freelancers and agencies. Pick your service, the client's industry, your experience and the result you deliver, choose a tone, and get a ready-to-send cold pitch in seconds.

**Live:** [emresenturer.github.io/pitchkit](https://emresenturer.github.io/pitchkit/)

## How it works

1. Paste your Anthropic API key (get one at [console.anthropic.com](https://console.anthropic.com/settings/keys)).
2. Fill in service, client industry, experience, key result and optional context.
3. Pick a tone (Confident, Warm, Formal, Bold) and generate.
4. Copy the pitch and send it.
5. Optional: write a Day 3 and Day 7 follow-up sequence that builds on the pitch.

No usage limits: every request runs on your own key.

## Templates pack

[PitchKit Templates Pack](https://senturer.gumroad.com/l/pitchkit), $17 one-time: 50 copy-paste pitch templates across 10 service niches, with cold emails, LinkedIn DMs and proposal intros.

## Privacy

- Your API key is stored only in your browser's localStorage and is sent only to `api.anthropic.com`.
- PitchKit has no backend, no analytics and no database. Your inputs go straight from your browser to the Claude API.
- Clear the key any time by clearing this site's data in your browser.

## Run locally

Single self-contained page, no build step:

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Stack

Vanilla HTML/CSS/JS, Claude API (`claude-opus-5-5`). By [Emre Senturer](https://github.com/emresenturer).
