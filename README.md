# Fisterdle

A daily guessing game for [Fister](https://fister.fun) cosmetics and maps.

**Cosmetics:** guess any cosmetic by Fister Team, PhoenixDoesStuff or joe. Each guess shows whether its **rarity**, **creator** and **type** match the answer:

- Green: match
- Orange: same area (for example a hat and a face are both head items)
- Red: no match. For rarity, an arrow shows whether the answer is rarer (↑) or more common (↓)

**Maps:** guess any public map. Each guess compares its **creator**, whether it's an **official or community** map, and its **game modes** (orange when they partly overlap).

The **Hint** button reveals the first letter, then the name length, then the first letter of each word.

**Daily** gives everyone the same cosmetic and map, wherever they are; it changes at midnight Pacific time. **Endless** gives a new one each round, and you can **Skip** to see the answer and move on.

## Updating the cosmetics

The cosmetic list is built into `index.html` (the `DATA` array). Each entry is `[name, type, rarity, creator, canBeAnswer, picture]`. Maps are in the `MAPS` array: `[name, creator, origin, gameModes, picture]`.

Fan-made; not affiliated with the Fister developers.

Page link: https://n7o-noob.github.io/fisterdle/
