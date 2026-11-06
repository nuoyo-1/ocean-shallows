# Ocean Shallows

A quiet, interactive tropical ocean in a single HTML file, built with Three.js r128 and WebGL.

一个单文件交互式浅海场景：海岸浪花、水面焦散、棕榈树影，以及可拖放的海洋生物。

## Run

Open `index.html` in a modern desktop browser. Internet access is required for Three.js and Google Fonts. No build step or package installation is needed. WebGL and GPU acceleration are recommended.

## Explore

Click a creature card to cast it into the sea, or drag it to place it in open water. Includes manta, spotted eagle ray, blue-spotted stingray, moon jelly and sea nettle, with animated model previews and a 48-creature limit.

Controls: **R** rain, **W** whirlpool, **C** calm, **M** sound, **H** hide/show interface. Drag the whirlpool to move it. Use Clear sea to remove placed creatures.

The scene includes GPU height-field ripples, refraction, caustics, swash, wet sand, baked seabed details and swaying palm shadows. Creature models are procedural; jellyfish have translucent bells and simulated ribbon tentacles. Reduced-motion preferences are supported. Rendering resolution adapts under load; performance varies by GPU.

## License and credits

MIT. See [LICENSE](LICENSE) and [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md). Jellyfish bell deformation references Aurelia by Holtsetio (MIT). Runtime: Three.js; fonts: Fraunces and Nunito Sans.
