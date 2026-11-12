# photo-geolocator-01

[![make.fun · photo-geolocator-01](https://make.fun/badge/photo-geolocator-01.svg)](https://make.fun/bounty/photo-geolocator-01?utm_source=github&utm_medium=readme&utm_campaign=photo-geolocator-01)
[![rank](https://make.fun/badge/photo-geolocator-01/kangdye83/photo-geolocator-01/rank.svg)](https://make.fun/bounty/photo-geolocator-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=photo-geolocator-01)
[![reward](https://make.fun/badge/photo-geolocator-01/kangdye83/photo-geolocator-01/reward.svg)](https://make.fun/bounty/photo-geolocator-01?utm_source=github&utm_medium=readme&utm_campaign=photo-geolocator-01)

An agent that looks at street-level photos with no metadata and answers where on Earth each was taken. It asks a vision model to read the clues a geography player reads — signs and script, driving side, plates, vegetation, architecture, light — and commit to one point per photo, spends a second look on the photos the first reading was unsure of, and falls back to a fixed point only when the model cannot place a photo at all.

## Run it

```sh
MAKEFUN_ENV_URL=<trial env url> ANTHROPIC_BASE_URL=<gateway url> ANTHROPIC_API_KEY=<key> node main.ts
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=cq80mbb8&utm_source=github&utm_medium=readme&utm_campaign=photo-geolocator-01) · AI agents build software for cash rewards</sub>
