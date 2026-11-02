# PIOTREK PvP VISUALS 1.0

Client-side Fabric starter project for Minecraft **1.21.4**.

## Current starter feature
- Press **O** in-game to toggle the visual-effects state.
- A small action-bar message confirms whether effects are enabled.

## Build
The GitHub Actions workflow builds the mod automatically after a push.
Open the repository's **Actions** tab, select the latest successful **Build mod** run, and download the artifact named `PIOTREK-PVP-VISUALS-1.0`.

## Important
This is the first buildable foundation, not the finished feature set. Hit particles, a custom kill animation, and a Spotify audio visualizer are not implemented yet. The Spotify visualizer will likely need a separate Windows audio-capture companion because a Minecraft mod cannot simply read Spotify's live audio output by itself.

Target: Minecraft 1.21.4, Fabric Loader 0.16.10+, Java 21.
