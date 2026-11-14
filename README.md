# melee-replay-components

Prebuilt files that Melee replay tools download and check by SHA-256. Nothing here is a game or contains game data; the Training Mode patch only does anything when applied to your own copy of Super Smash Bros. Melee (NTSC 1.02).

| File | What it is | From |
|---|---|---|
| `melee-sim-light-05447200e4.zip` | A Windows build of the replay driver of melee-sim-light (commit 05447200e4) and the Python that runs it | [kyhavlov/melee-sim-light](https://github.com/kyhavlov/melee-sim-light), by enzyme |
| `gx-core.js`, `gx-core.wasm` | The same simulator built for the browser, for drawing replays in 3D | melee-sim-light, which is built from the [doldecomp/melee](https://github.com/doldecomp/melee) decompilation |
| `tmce-practice-loop-804a49e.xdelta` | A patch that turns your Melee ISO into a practice-loop build of Training Mode - Community Edition | [AlexanderHarrison/TrainingMode-CommunityEdition](https://github.com/AlexanderHarrison/TrainingMode-CommunityEdition) by Aitch, on [UnclePunch's Training Mode](https://github.com/UnclePunch/Training-Mode) |

These files belong to their authors and are not covered by any license of this repository. Super Smash Bros. Melee is Nintendo's; nothing here is affiliated with or endorsed by Nintendo.

## Checksums (SHA-256)

```
354f368ce96d6f703b109de9aeefae7d96cd912dbd677221d2dd18c3e71f5b10  melee-sim-light-05447200e4.zip
95d78af93fc712a586159f0c2e620d47926c6fbb44716a9bdde457d63055834e *gx-core.js
4eed7201eea53ac3e94a605e6d3ce4e35fef864e89d18c9d0128a304d8899941 *gx-core.wasm
37beb2f2624cff29a1bc8c85b808d36041b3158cdbd727a5b80cc138551b08fe *tmce-practice-loop-804a49e.xdelta
```
