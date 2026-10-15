<picture>
  <source media="(prefers-color-scheme: dark" srcset="./assets/banner-dark.svg">
  <img src="./assets/banner-light.svg" alt="Davi Pinto Ferreira, full-stack developer" width="100%">
</picture>

<p align="center">
  <a href="https://davipferr.github.io/"><img src="https://img.shields.io/badge/Portfolio-davipferr.github.io-0ea5e9?style=flat-square&logo=githubpages&logoColor=white" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/davipferr/"><img src="https://img.shields.io/badge/LinkedIn-davipferr-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <img src="https://img.shields.io/badge/São_Paulo-Brazil-16a34a?style=flat-square&logo=googlemaps&logoColor=white" alt="São Paulo, Brazil">
</p>

## About

I'm a full-stack developer who likes turning **real data into things you can explore**. Most of my recent work falls into three areas:

- **Live 3D on the web**: public APIs (USGS, NOAA, OpenF1, CelesTrak) rendered in the browser with Three.js, with no backend.
- **Data stories**: one question, an open dataset, a Python pipeline and an interactive site that answers it.
- **Building from scratch**: small versions of React, Vite or a vector database, written to learn how the real ones work.

Professionally I've worked with **C# / .NET**, **PHP / Laravel** and **Vue.js**.

## Featured work

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🏎️ F1 Replay</h3>
      <p>Real Formula 1 races replayed in 3D: every car's position about four times a second, plus timing, tyres, pit stops, weather and telemetry.</p>
      <p><code>TypeScript</code> <code>Three.js</code> <code>OpenF1</code></p>
      <p><a href="https://davipferr.github.io/f1-replay/"><b>Live demo</b></a> · <a href="https://github.com/davipferr/f1-replay">Source</a></p>
    </td>
    <td width="50%" valign="top">
      <h3>🛰️ Real LiDAR Flyover</h3>
      <p>Fly over USGS airborne laser scans of up to billions of points, streamed on demand and decoded in Web Workers with WebAssembly.</p>
      <p><code>TypeScript</code> <code>Three.js</code> <code>WASM</code></p>
      <p><a href="https://davipferr.github.io/real-lidar-flyover/"><b>Live demo</b></a> · <a href="https://github.com/davipferr/real-lidar-flyover">Source</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🌐 Satellite Tracker</h3>
      <p>Real-time 3D satellite positions built from first principles, with live orbital data from CelesTrak propagated by SGP4.</p>
      <p><code>TypeScript</code> <code>Three.js</code> <code>CelesTrak</code></p>
      <p><a href="https://davipferr.github.io/satellite-tracker/"><b>Live demo</b></a> · <a href="https://github.com/davipferr/satellite-tracker">Source</a></p>
    </td>
    <td width="50%" valign="top">
      <h3>🌋 Earthquake Globe</h3>
      <p>Live USGS earthquakes on a 3D globe. In X-ray mode each quake sits at its real depth inside a translucent Earth.</p>
      <p><code>TypeScript</code> <code>Three.js</code> <code>USGS</code></p>
      <p><a href="https://davipferr.github.io/earthquake-globe/"><b>Live demo</b></a> · <a href="https://github.com/davipferr/earthquake-globe">Source</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🌌 Aurora &amp; Space Weather</h3>
      <p>A live aurora forecast on a globe plus a space-weather dashboard, fed straight from NOAA's Space Weather Prediction Center.</p>
      <p><code>TypeScript</code> <code>Three.js</code> <code>NOAA</code></p>
      <p><a href="https://davipferr.github.io/aurora-and-space-weather-dashborad/"><b>Live demo</b></a> · <a href="https://github.com/davipferr/aurora-and-space-weather-dashborad">Source</a></p>
    </td>
    <td width="50%" valign="top">
      <h3>🌊 Real Ocean</h3>
      <p>The sea at a real beach, right now: swell, tide, sun, moon, clouds and rain for that place and hour.</p>
      <p><code>TypeScript</code> <code>Three.js</code> <code>Open-Meteo</code></p>
      <p><a href="https://davipferr.github.io/real-ocean/"><b>Live demo</b></a> · <a href="https://github.com/davipferr/real-ocean">Source</a></p>
    </td>
  </tr>
</table>

<details>
<summary><b>More 3D experiments</b></summary>
<br>

| Project                                                           | Description                                                           |
| ----------------------------------------------------------------- | --------------------------------------------------------------------- |
| [Voxel Pokédex](https://davipferr.github.io/voxel-pokedex/)       | Every Pokémon sprite rebuilt as 3D voxels that explode and reassemble |
| [Music Visualizer](https://davipferr.github.io/music-visualizer/) | Search any song and watch it as a 3D landscape                        |
| [Voxel MTG](https://davipferr.github.io/voxel-mtg/)               | Magic cards as voxel slabs, with the art's subject popping out        |

</details>

## Data stories

Built with a **Python (Polars)** pipeline and **Observable Framework**. All data is processed at build time, so the sites are fully static.

| Story                                                                               | The question                                                                     |
| ----------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- |
| [**The Shape of Stories**](https://davipferr.github.io/the-shape-of-stories/)       | Do novels really follow a handful of emotional arcs? A re-analysis of 955 books. |
| [**Pokémon Power Creep**](https://davipferr.github.io/pokemon-power-creep/)         | Are newer Pokémon stronger than older ones?                                      |
| [**Forecasts vs. Reality**](https://davipferr.github.io/forecasts-vs-reality/)      | How good are forecasters compared with "nothing changes"?                        |
| [**Car Depreciation Curves**](https://davipferr.github.io/car-depreciation-curves/) | How fast do cars lose value in Brazil? (FIPE data, inflation-adjusted)           |

## Built from scratch

| Project                                                                             | What it rebuilds                                                     |
| ----------------------------------------------------------------------------------- | -------------------------------------------------------------------- |
| [**mini-react**](https://github.com/davipferr/mini-react)                           | A React/Preact look-alike in about 245 lines, with no dependencies   |
| [**mini-vite**](https://github.com/davipferr/mini-vite)                             | A ~1,400-line Vite clone: what actually happens on `npm run dev`     |
| [**mini-framer-motion**](https://github.com/davipferr/mini-framer-motion)           | Framer Motion in TypeScript + React 19, with hand-integrated springs |
| [**retrieval-from-scratch**](https://github.com/davipferr/retrieval-from-scratch)   | A search engine and vector database in Rust, feeding a RAG chat app  |
| [**learn-network-protocols**](https://github.com/davipferr/learn-network-protocols) | Real Go clients and servers that show protocols byte by byte         |

## Tech stack

<p>
  <img src="https://skillicons.dev/icons?i=ts,js,cs,py,rust,go,php" height="44" alt="Languages: TypeScript, JavaScript, C#, Python, Rust, Go, PHP"><br><br>
  <img src="https://skillicons.dev/icons?i=threejs,vite,vue,vuetify,dotnet,laravel,nodejs" height="44" alt="Frameworks: Three.js, Vite, Vue, Vuetify, .NET, Laravel, Node.js"><br><br>
  <img src="https://skillicons.dev/icons?i=mysql,mongodb,git,github,githubactions,linux" height="44" alt="Tools: MySQL, MongoDB, Git, GitHub, GitHub Actions, Linux">
</p>

---

<p align="center">
  <sub>Open to conversations and collaborations. The best way to reach me is <a href="https://www.linkedin.com/in/davipferr/">LinkedIn</a>.</sub>
</p>
