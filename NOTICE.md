# Notices

## The picture

The backdrop in this theme is the Ember scene from
[neverblinks/backdrops](https://github.com/neverblinks/backdrops), copied at the commit in `vendor/backdrops/COMMIT`.

- `vendor/backdrops/scene-ember.js` is upstream's file, unchanged.
- `theme.json` embeds that scene unchanged, escaped for a CSS `url("data:...")`. `check.mjs` reverses the escaping and
  requires the result to equal the scene.

Upstream splits its terms in two, and both files are copied here unchanged:

- `vendor/backdrops/LICENSE`: the MIT License, for upstream's code. Copyright (c) 2026 neverblinks.
- `vendor/backdrops/ARTWORK.md`: the terms for the pictures, which the MIT licence does not cover. It counts every
  `scene-*.js` file as a picture.

From `ARTWORK.md`, for Ember:

- The picture is a warm glow in the corner of a dark, grainy screen, © 2026 neverblinks.
- Anyone may install and use the theme for free, for any purpose, and may share links to upstream's repository.
- Without permission, nobody may sell the picture or anything made from it, redistribute it outside
  upstream's repository, claim it as their own, or remove or hide the credits.

The scene file and `theme.json` both contain the picture. This repository is private for that reason.
Before you make it public or pass `theme.json` on, ask neverblinks.

## This repository's own code

`build.mjs` and `check.mjs` are under the MIT License in `LICENSE`. The palette in `build.mjs` is upstream's, from
`plugins/backdrops/hooks/look-ember.ts`.

## T3 Code

This theme is not affiliated with or endorsed by T3 Code. The screenshots show T3 Code running with an invented
demo project.
