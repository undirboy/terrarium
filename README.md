AI Self-Sustaining Digital Terrarium
A zero-dependency, single-file web application featuring a living, breathing digital terrarium. Procedural flora mutate, grow, and release ambient particles in real-time, completely driven by the live weather conditions and day-night cycle of your actual GPS coordinates.

Features
Zero Dependencies: Built entirely with vanilla ES6 JavaScript, HTML5 Canvas, and CSS. No bundlers, npm packages, or external graphic assets required.

Biometric & GPS Integration: Automatically detects user coordinates via browser geolocation and syncs real-time environmental data using the free Open-Meteo API.

Procedural Morphogenesis: Plant structures, segment counts, fractal angles, branch thicknesses, and color phenotypes compute dynamically and mutate based on environmental triggers.

Dynamic Ecosystem Physics: Ambient particles shift states (spores at night, oxygen motes during the day) and drift organically according to live wind velocity and temperature gradients.

Interactive Controls: Force rapid AI-induced mutations or reset the ecosystem seed directly from the glass-morphism overlay UI.

Quick Start
Save the application code into a single file named index.html.

Open index.html directly in any modern web browser (Chrome, Safari, Firefox, Edge).

Allow browser geolocation permissions when prompted to sync the terrarium to your local environment. (If denied or offline, the app gracefully falls back to a default synthetic climate grid).

How It Works
The application initializes a continuous rendering loop split into three core engine layers:

Environment Fetcher: Queries regional weather conditions (temperature, humidity, wind speed, solar day/night flags) upon startup.

Procedural Generator (ProceduralPlant): Instantiates fractal plant stalks using mathematical parameters mapped directly to local atmospheric data (e.g., higher humidity yields taller stalks; temperature alters color hues).

Particulate Simulator (AmbientParticle): Continuously emits environmental markers from plant terminal nodes, reacting dynamically to ambient wind vectors and time-of-day illumination gradients.

Customization
Because the entire application resides in a single self-contained file, you can easily modify core simulation constants directly within the <script> block:

Adjust plant density scaling factors inside buildEcosystem().

Modify particle spawn frequency or wind coefficients in the DigitalTerrarium update loop.

Customize the glass-morphism UI styles inside the <style> block.

License
Distributed under the MIT License. Feel free to fork, modify, and expand your digital ecosystem.
