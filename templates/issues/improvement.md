## ✨ Improvement

**File / cue affected:** `Fresh_and_Clean/<category>/<event>.ogg`

## What's off right now?

_Describe the problem — too loud, too long, clashes with neighbours, wrong character._

## Target spec

| Metric | Current | Target |
|--------|---------|--------|
| Loudness (LUFS integrated) | | −16 ±1 LUFS |
| Peak (dBFS) | | ≤ −1 dBFS |
| Duration | | |

## Done when

- [ ] A/B comparison against current cue passes a listener test
- [ ] Spectrogram clean — no 2–5 kHz fatigue spikes
- [ ] `ffmpeg -af ebur128` confirms loudness target
- [ ] `paplay` smoke test passes on ≥ 2 distros
- [ ] No neighbouring cues regressed

/label ~enhancement ~audio
