## 🎧 Audio Contribution

**Event name:** `<event-name>`  
**File:** `Fresh_and_Clean/<category>/<event>.ogg`

## Measurements

Run: `ffmpeg -i <file>.ogg -af ebur128 -f null -`

| Metric | Value | Spec |
|--------|-------|------|
| Loudness (LUFS integrated) | | −16 ±1 LUFS |
| Peak (dBFS) | | ≤ −1 dBFS |
| Duration | | notifications ≤ 500ms · UI cues ≤ 200ms |

## Spectrogram

_Paste screenshot or note findings. Flag any energy in the 2–5 kHz fatigue band._

## Smoke test

- [ ] `paplay <event>.ogg` — clean, no distortion or clipping
- [ ] Tested on: <!-- distros + audio backends -->

## Checklist

- [ ] CI `audio-qa` stage green
- [ ] File in correct Freedesktop category directory
- [ ] No unrelated cues touched

Closes #
