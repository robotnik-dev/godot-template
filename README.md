# {{ Game Name}}

![CI](https://github.com/robotnik-dev/godot-template/actions/workflows/ci.yaml/badge.svg)

# CI
1. For the CI to run you have to push a new tag in the format

        v*.*.*

    The same tag will be used to deploy the game to different platforms.

2. Set the following repository variable

        ITCHIO_GAMENAME

# Deployment via butler
## HTML browser game

If nothing runs in the browser you have to [tag the channel](https://itch.io/docs/butler/pushing.html#html--playable-in-browser-games)
```
Tagging a channel as 'HTML5 / Playable in browser' needs to be done from the itch.io Edit game page, once the first build is pushed.

The page also needs to be set to 'HTML' rather than the default 'Downloadable'.
```