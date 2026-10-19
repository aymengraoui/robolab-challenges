# RoboLab challenges

The monthly competition courses for RoboLab. The game downloads `challenges.json` at start, keeps a copy, and
falls back to the course built into it when offline.

Each challenge is a list of pieces laid end to end like toy track (`straight` or `arc` + `radius`, with optional
`rise`, `line`, `walls`, or a coloured `zone`). The game checks every course before building it and skips one
that doesn't fit the arena, so a mistake here never breaks the game.
