# ⚔️ C-Tekken P2P Multiplayer Arcade

A peer-to-peer (P2P) browser-based multiplayer fighting game utilizing a custom C-style grid game engine. Players can connect across different devices from anywhere in the world using simple 4-digit room codes—completely hosted for free via GitHub Pages with no dedicated server required.

## 🌐 How Multiplayer Works (PeerJS / WebRTC)
1. **Player 1 (Host)** clicks **"Create Room"**, generating a secure 4-digit room code.
2. **Player 2 (Joiner)** inputs the room code on their mobile device or laptop and clicks **"Join Room"**.
3. **Direct P2P Link:** The browsers establish a direct, low-latency data channel, synchronizing game state and turns instantly across devices.

## 🕹️ Game Mechanics
* **Engine Logic:** Custom coordinate mapping tracking Player 1 (`O`) and Player 2 (`o`) across a $12 \times 45$ grid.
* **Turn Enforcement:** Strict client-side turn validation prevents out-of-order moves and maintains synchronized health states (`100 HP` starting).
* **Mobile & Desktop Ready:** Features optimized touch controls and responsive layouts for phone browsers.

## ⌨️ Controls
* **Movement:** `W`, `A`, `S`, `D` / On-Screen D-Pad
* **Combat:** `F` (Punch), `G` (Kick)

[Live demo - https://siddharth9234.github.io/tekken-personal-room-game/ ]
