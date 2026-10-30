# Contributing to Foil Engine

Thanks for your interest. The project is young: the most useful contributions right now are **reports of rules applied incorrectly**, with a replay.

## Reporting a rule applied incorrectly

Use the "Rule applied incorrectly" issue template in `foilengine`: the exact rule number in the Core Rules, the rules version, what the rule says, what the engine does, and the game ID (or the replay file). Without a replay, we can't reproduce it.

## Language

The project works in English: issues, PRs, commits, code and comments.

## Contributing code

1. Read the `README.md` and `docs/` of the `foilengine` repository, especially `docs/13-conventions.md` and `docs/06-testing.md`.
2. Open an issue first to discuss what you want to do.
3. One PR, one topic. Every implemented rule has a test that cites its Core Rules number.
4. CI must pass (lint, typecheck, tests, short fuzzing run).

## What we don't accept

- Anything that would make the project paid, in any form.
- Riot logos or trademarks in the project's identity.
- A guessed rule: when in doubt, open a rules question.
