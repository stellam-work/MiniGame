# Mini-Game Studio

A reusable, GitHub/CLI-first studio for producing original **illustrated-narrative mini-games**, built for iPad-sized touchscreens and equivalent desktop mouse interaction.

## Read first

- [Visual & Interaction Bible v1](bible/VISUAL_BIBLE.md) — authoritative visual identity, shapes, shading, layering, eight exact brand colours and Fraunces + Nunito Sans typography.
- [Mini-Game Studio Agent: Master Operating Prompt](agents/MINI_GAME_STUDIO_AGENT.md) — repeatable process covering story intake, adaptive interviews, mechanics research, illustration, implementation, localisation, testing and delivery.
- [Lessons log](LESSONS.md) — record technical and narrative discoveries reusable across games.

## Workflow

1. User supplies a story and game concept; agent investigates mechanics rather than inventing a new story.
2. Agent interviews adaptively, researches suitable mechanics and prepares concept, mechanics, brief, first asset and sample scenes.
3. **One consolidated user approval gate.** No full production before sign-off.
4. Agent develops approved game autonomously with CLI tools, original artwork, source code and separate language files.
5. Run functionality and narrative-flow QA; deliver source and self-contained production build. Update LESSONS.md.

## Requirements across games

- Fullscreen / standalone iPad-sized presentation, touch-first and mouse-equivalent interactions, no keyboard dependency.
- English, Italian, French, German, Dutch, with narrative text in external localisation files.
- Prefer standalone builds with local runtime assets, usable on a web host or local static server.
- Shared illustrated narrative brand, with flexible game-specific accent colours and mechanics.
- Scope testing to functionality and story flow; distinguish real hardware from emulation.

## Structure

```text
bible/VISUAL_BIBLE.md
agents/MINI_GAME_STUDIO_AGENT.md
games/<game-slug>/             # game brief, sample scenes, src, locales, tests, assets
shared/                       # reusable components as created
LESSONS.md
```

## Status

**Studio foundation only.** No game runtime, production artwork, test run or deployable game is yet included. Reference screenshots provided in the design discussion are not committed to this public repo; only original or suitably licensed media should be added.

## Local use

```sh
git clone https://github.com/stellam-work/MiniGame.git
cd MiniGame
git checkout feature/mini-game-studio-v1
```

New games will have their own `package.json` and documented `npm ci`, `npm run dev`, `npm run build`, `npm run test` scripts where appropriate. There is intentionally no root game executable yet.
