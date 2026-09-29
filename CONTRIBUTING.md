# Contributing

Thanks for wanting to help. A few things to know before you open something.

## Bugs

Open an issue in the repository the bug belongs to: `pack` for anything you see in game (crashes, broken recipes, a mod behaving oddly), `core` for the server mod (slots, goals, commands, the spawn block). Use the template, attach the log or the crash report as a file, not a screenshot.

## Ideas

Open an issue with the idea template. Say what problem it solves for players, not only what it is. Ideas that fit the season's theme and can be built in a week have the best chance.

## Pull requests

- One change per pull request, with a short description of why.
- The pack: change it with packwiz, never by hand-editing the index. Test with a fresh instance before opening the PR.
- The mod: `./gradlew build` must pass. Keep the code style of the file you are in.
- Commit messages: `feat:`, `fix:`, `docs:`, `build:`, `ci:`, `refactor:`, imperative, under 70 characters.

## Licences

Contributions to `core` are under the MIT licence of the repository. The pack only references mods; each mod keeps its own licence.
