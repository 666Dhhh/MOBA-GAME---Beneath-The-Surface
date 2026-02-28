
🦈 DEEP-SEA RUPTURE
A Subterranean Combat Engine built for Campfire Seattle 2026.

🕹️ LIVE DEMO: PLAY IN BROWSER [https://666dhhh.github.io/MOBA-GAME---Beneath-The-Surface/]

Best experienced on Chrome/Edge. Use a keyboard to hunt.

The Concept: "Beneath the Surface"
Most games treat the ground as a static texture. In Deep-Sea Rupture, the ground is a fragile veil.

You play as a predator in a shark cowl, but you aren't just a guy in a costume—you're an abyssal force. We took the theme "Beneath the Surface" and baked it into the core combat loop: your power doesn't come from the air or the sky; it erupts from the tectonic pressure below.

Key Features
🌋 Sub-Surface Eruption (The Ultimate)
Forget standard projectiles. The Abyssal Breach (L key) triggers a screen-shaking displacement effect. We developed a custom beneathSurface rendering logic that fractures the map's coordinate system, simulating a predator breaching from the dark depths. It’s not just an attack; it’s a geological event.

🌑 Atmospheric Pressure (Fog of War)
We ditched the standard "black overlay" for a radial-gradient vision system. It mimics the claustrophobic feeling of deep-sea diving. If you can't see them, they're probably already under you.

🧠 Predatory "Kite-and-Kill" AI
The bots aren't punching bags. They run a dynamic distance-evaluation script that makes them "shiver" and retreat like panicked prey when low on health, or dash in for a frame-perfect execution if they smell blood.

Technical Specs
Vanilla JS + Canvas API: Zero frameworks. No React, no Three.js. Just raw, high-performance DOM manipulation and a 60FPS render loop.

Layered VFX Pipeline: A custom stack to handle real-time screen shake, particle physics, and alpha-blended light gradients without dropping frames.

Modular Shop System: A base-proximity-checked inventory that handles stat scaling (ATK/HP) on the fly.

Controls
WASD — Stalk.

I (Dash) — Breach the gap.

L (Ult) — Fracture the earth.

P (Shop) — Evolve (Only available at the "Reef" / Spawn).

Tab — Check the Food Chain.

🚀 Developer's Note
The goal was to make the player feel the "weight" of the abyss. Every time the ground cracks or a dash leaves a trail of bubbles, it's a reminder that you're the one thing that doesn't belong on the surface.

