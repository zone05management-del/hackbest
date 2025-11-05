# Simulated Hacker Dashboard — Safe Demo

This is a purely simulated, client-side demo of a neon "ACCESS NODE" dashboard and several detail pages (Phones, Cars, Bank). It uses mock JSON data and local UI-only logic — no real device access or hacking functionality.

Important:
- This project is for demonstration, design and educational purposes only. It does not perform any network attacks, unauthorized access, or connect to real systems.
- Do not use this code for illegal activity.

Quick start (serve locally):
- Using Python:
  - python3 -m http.server 8000
  - Open http://localhost:8000
- Or with Node:
  - npx serve .
  - Open http://localhost:5000 (or shown port)

User flow:
- Login page -> Dashboard -> Phones / Cars / Bank.
- Demo passphrase: `rodgerfox` (keeps the original demo behavior).
- All data is loaded from `data/*.json` and simulated on the client.

If you want more pages or features (simulated maps, more apps inside the phone, richer car telemetry, or a mock attacker/observer mode for training), tell me which specific features and I’ll expand the simulation.