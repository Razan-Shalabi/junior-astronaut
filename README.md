# Junior Astronaut

A 3D educational space adventure for children aged 7 to 12, built by team SHEclipse for the NASA Space Apps Challenge 2026 ("Build a Junior Astronaut Mission Trainer").

The player receives a mysterious invitation, is flown by spaceship to a desert, and learns step by step what it takes to explore Mars. Nuri, a small alien AI companion, explains and gives hints but never solves a challenge for the player. The game runs in English and Arabic.

## Play it

Open `index.html` in a modern browser. An internet connection is needed the first time, because the page loads Three.js and its fonts from a CDN. There is nothing to install or build.

Controls: WASD or arrow keys to walk, Shift to run, Space to jump, drag to look around, E to interact. On phones and tablets there is an on-screen joystick.

## What is in the game so far

**Prologue: The Invitation**
- A space-themed bedroom with a glowing box to open
- A full-screen invitation addressed to the player by name
- A spaceship with a green beam, and a flight over mountains and the sea
- Landing in a mystery desert and meeting Nuri

**Level 1: The Secrets of the Atacama Desert**
- Task 1: fix a broken world-map puzzle to find out where you are (Atacama Desert, Chile)
- Free exploration with three discoveries: very dry ground, wind-shaped rocks and dunes, and life in the desert
- A hilltop view where Nuri explains how Mars differs from Earth
- The Junior Astronaut Training Academy appears, leading to Level 2

**Level 2: Junior Astronaut Training Academy**

Five training rooms. Each one earns a stamp in the Astronaut Passport, and all five open the launch bay.
1. Find Your Destination: explore a moving solar system, pick Earth and Mars, wait for the launch window, and choose the curved route that meets Mars where it will be
2. Suit Up!: drag the helmet, gloves, boots and life support pack onto a training dummy, then test pressure, oxygen and cooling
3. Pack for Survival: load the cargo bay within a 100-point limit, keeping water, food, medicine and tools
4. Systems Check: find the system with a warning (power or communication) and fix it
5. Mission Emergency!: power drops to 6 units, so choose which systems stay on

Level 3 (launch to Mars) is not built yet. The title screen has shortcuts to jump straight to Level 1 or Level 2.

## Science

The facts in the game are kept consistent with NASA sources. The Atacama Desert is used by scientists, including NASA-supported teams, as a Mars analog: a place on Earth that is similar to Mars in some ways, such as being extremely dry.

This project is not an official NASA product and does not use the NASA logo.

## Files

| File | What it is |
| --- | --- |
| `index.html` | The current game: prologue and Level 1, in one self-contained page |
| `prototypes/level1-science-stations.html` | An earlier Level 1 with packing, a soil lab, a salt rock, a rover drive and a telescope |
| `prototypes/red-base-explorer-3d.html` | An earlier 3D prototype: running a Mars base for seven sols |
| `prototypes/mission-red-base.html` | The first 2D prototype of the Mars base game |

## Notes

- Sounds and music are generated in the browser with the Web Audio API, so there are no audio files.
- Nuri's free-text chat and read-aloud voice only work when the game is opened as a Claude artifact. Elsewhere, Nuri answers from a fixed set of questions and hints.
