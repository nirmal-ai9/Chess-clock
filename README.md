# Chess Clock

Over-the-board chess clock with a monochrome flip theme — the whole screen becomes the board, flipping to white on White's turn and black on Black's turn. Built as a single, dependency-free HTML file.

---

### Features

- **Flip-theme display** — the screen itself is the indicator: white ground for White's move, black ground for Black's
- **Time controls** — Bullet, Blitz, Rapid, Classical presets, plus a custom minutes + increment option
- **Fischer increment** — time added back per move, per player
- **Low-time warning** — switches to tenths-of-a-second display and pulses under 20 seconds
- **Pause / resume** and **new game** controls
- **Keyboard accessible** — space/enter passes the turn, focus states, live region announcements for screen readers
- **Reduced-motion aware** — respects `prefers-reduced-motion`

---

### Usage

Open `index.html` in any browser. Pick a time control (or set a custom one), hit **Start game**, then tap/click the panel — or press space/enter — to pass the turn after each move.

---

### Stack

`HTML` `CSS` `JavaScript` — no frameworks, no build step, no dependencies.

### Author: Nirmal

<div align="center">

<a href="https://nirmal-ai9.github.io/portfolio/">
  <img src="https://img.shields.io/badge/Visit_My_Portfolio-000000?style=for-the-badge&logo=apple&logoColor=white" alt="Visit Portfolio" />
</a>

</div>
