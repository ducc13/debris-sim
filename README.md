# Orbital Debris Simulator

A real-time, physics-based simulator of satellites and orbital debris, built in Unity (C#) and playable in the browser.

**Live demo:** https://ducc13.github.io/debris-sim/

I built this as a summer 2026 intern at the Indian Institute of Space Science and Technology (IIST), Trivandrum.

## What it does

* Models satellite orbits using orbital mechanics principles
* Detects collisions between objects
* Generates debris when collisions occur
* Visualizes everything in real time
* Includes interactive dashboards for watching and controlling the simulation

## Tech

* Unity
* C#
* Unity WebGL build, hosted on GitHub Pages

## How to run

Open the live demo link above in a desktop browser. No install needed.

To run locally, serve this folder with any static web server (browsers block WebGL builds opened directly from the file system), for example:

```bash
python -m http.server 8000
```

Then open http://localhost:8000.

## Controls

* **Mouse wheel:** zoom in and out
* **Right-click + drag:** rotate the view around the Earth

## Screenshot

<!--add screenshot later-->

## Repository contents

This repository contains the WebGL build only:

* `index.html` – page that loads the simulator
* `Build/` – compiled Unity WebGL output
* `TemplateData/` – Unity's default loader assets

## Author

Rishon Daniel Varghese – B.Tech ECE, IIIT Bangalore

