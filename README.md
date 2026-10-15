# Fisterdle

A daily guessing game for [Fister](https://fister.fun) cosmetics.

Guess any cosmetic by name. Each guess shows whether its **rarity**, **creator** and **type** match the answer:

- Green: match
- Orange: same area (for example a hat and a face are both head items)
- Red: no match. For rarity, an arrow shows whether the answer is rarer (↑) or more common (↓)

The **Hint** button reveals the first letter, then the name length, then the first letter of each word.

**Daily** gives everyone the same cosmetic, and it changes at midnight in your timezone. **Endless** gives a new one each round.

## Updating the cosmetics

The cosmetic list is built into `index.html` (the `DATA` array). Each entry is `[name, type, rarity, creator, canBeAnswer]`.

Fan-made; not affiliated with the Fister developers.
