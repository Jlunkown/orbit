# Orbit (Submission for GameDevTv game jam 2022)

<img src="Assets/player/art/ball%20robot%201.png" alt="Orbit" width="96">

A top-down shooter made in Unity. You control a robot named Orbit and go around the map finding power-ups, which are given to Orbit after you die. Death is only the beginning.

**Play it on itch.io:** https://jlunknown.itch.io/orbit (runs in the browser)

## How to play

| Input | Action |
| --- | --- |
| Mouse | Aim / turn Orbit |
| W | Thrust forward |
| W / S (or ↑ / ↓) | Move forward / back once you have the **control** power-up |
| Left click | Shoot once you have the **gun** power-up |

Orbit starts with almost nothing: no gun and only drifting thrust. Power-ups you pick up carry over into your next life:

- **Gun**: lets Orbit shoot
- **Health**: more max health
- **Control**: proper movement instead of drifting
- **Attack speed**: shoot faster

There's a start screen, a tutorial, five levels and a boss.

## Opening the project

1. Install **Unity 6000.0.24f1** (Unity 6) through Unity Hub.
2. Clone this repo and add the folder in Unity Hub (**Add → Add project from disk**).
3. Open `Assets/Scenes/startScene.unity` and press Play.

Builds go through **File → Build Profiles**: Web for the itch.io version, or Windows.

## Project layout

```
Assets/
  player/        Orbit's movement, shooting and sprites
  enemy/         enemies and the boss
  powerups/      power-up pickups and the key
  bullet/        projectiles
  UI/            health bars, buttons, music
  wall floor/    level tiles and lasers
  Scenes/        startScene, Tutorial, level 1–5
  scripts for scene stuff/   level flow and keeping power-ups between deaths
```

## Credits

Made by [Jlunknown](https://jlunknown.itch.io).
