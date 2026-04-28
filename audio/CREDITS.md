# Audio Credits

All ambient loops are sourced from Mixkit and processed for use in HODL FM.

## Source

**Mixkit** (https://mixkit.co) — Mixkit Stock Music Free License
https://mixkit.co/license/#musicFree

The Mixkit Stock Music Free License grants free use for both personal and commercial projects, including monetized content. No attribution required (provided as courtesy).

## Tracks

- **falling.ogg** — based on "Shame" by Eugenio Mininni (Electronica) — https://mixkit.co/free-stock-music/track/553/
- **cooling.ogg** — based on "Vastness" by Andrew Ev (Ambient) — https://mixkit.co/free-stock-music/track/184/
- **still.ogg** — based on "Mountains" by Andrew Ev (Electronica) — https://mixkit.co/free-stock-music/track/187/
- **rising.ogg** — based on "Drawing the Sky" by Eugenio Mininni (Orchestral Pop) — https://mixkit.co/free-stock-music/track/606/
- **surge.ogg** — based on "Skyline" by Eugenio Mininni (Classical) — https://mixkit.co/free-stock-music/track/601/

## Processing

For each track:
1. The most uniform 24-second segment was selected via RMS variance analysis
2. Two layers mixed with a 12-second offset for additional smoothness (eliminates phrase dynamics)
3. State-specific lowpass filter applied (FALLING 1400 Hz → SURGE 4500 Hz)
4. Highpass at 40 Hz to remove rumble
5. Crossfade in/out at 0.5s for seamless looping
6. Normalized to -18 LUFS via volume gain (avoiding loudnorm linear=true sample-rate issues)
7. Encoded as OGG Vorbis q:a 4 at 48 kHz stereo

All processing performed with ffmpeg.
