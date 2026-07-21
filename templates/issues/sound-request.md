## 🎵 Sound Request

**Freedesktop event name:** `<event-name>`  
_([Sound Naming Spec](https://www.freedesktop.org/wiki/Specifications/sound-theme-spec/) — use the canonical name, not a made-up one.)_

## Why does this need a cue?

_What action or state change should trigger it? What does the user gain from hearing it?_

## Done when

- [ ] `<event-name>.ogg` in the correct Freedesktop category directory
- [ ] −16 ±1 LUFS · peak ≤ −1 dBFS · duration within spec
- [ ] Spectrogram clean — no fatigue spikes in 2–5 kHz
- [ ] `paplay` smoke test passes on Debian, Arch, Fedora

/label ~enhancement ~audio
