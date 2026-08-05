# Awesome Codex Pets

A collection of custom pets for [Claude Codex](https://claude.ai/code), featuring animated sprite companions for your coding sessions.

## Pets

| Pet | Description |
|-----|-------------|
| **Climber Cat** | A bold white cat decked out in climbing gear — harness, chalk bag, and approach shoes — always ready for the next send. |
| **Belayer Cat** | A vigilant black-and-white cat kitted out with a belay device and harness, keeping a watchful eye on every climb. |
| **Chotu** | A cheerful, brave young hero who keeps you company while you work — a fan-made pet inspired by *Chhota Bheem*. |

## Structure

```
pets/
  <pet-slug>/
    pet.json          # Pet metadata and spritesheet config
    spritesheet.webp  # Animated sprite frames
    submission.json   # Submission metadata for the pet registry
pets.json             # Index of all pets in this collection
```

## Adding a Pet

1. Create a new directory under `pets/<your-pet-slug>/`
2. Add `spritesheet.webp` with your animated sprite frames
3. Add `pet.json`:
   ```json
   {
     "id": "your-pet-slug",
     "displayName": "Your Pet Name",
     "description": "A short description.",
     "spritesheetPath": "spritesheet.webp",
     "kind": "animal"
   }
   ```
4. Add `submission.json` with author and tag metadata
5. Add an entry to `pets.json`

## License

MIT License — see individual `submission.json` files for per-pet licensing.
