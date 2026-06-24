Yona Chat 🕊️
Yona Chat is a lightweight, decentralized, peer-to-peer (P2P) web application designed for secure and private communication. Inspired by modern chat interfaces like Discord, it offers a real-time messaging workspace entirely driven by WebRTC technology directly inside your browser—no heavy backend servers or databases required.

🚀 Features
True P2P Connectivity: Text data travels directly from browser to browser using WebRTC data channels, ensuring absolute privacy.

6-Digit Room Syncing: Effortlessly bridge connections by sharing a simple, temporary 6-digit room code rather than handling massive, complex Base64 session strings.

Dynamic Identity: Allows you to pick a custom username before hosting or joining a channel.

Sleek Dark Theme: Built with a clean UI modeled after professional chat platforms, complete with an embedded high-resolution vector logo.

Serverless Architecture: Completely self-contained within a single, lightweight HTML file. It relies on a public MQTT broker strictly for the initial handshake before shutting down the pipeline to let your direct connection take over.

🛠️ How It Works
Host: Click Generate 6-Digit Code to create a private signaling room.

Join: Share the 6-digit code with your peer. They enter it and hit Join Room.

Connect: Once the initial network handshake completes automatically in the background, the application safely disconnects from the public signaling bridge and opens a direct, hyper-fast peer-to-peer connection.

