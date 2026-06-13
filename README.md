⚡ TypeForge
Professional Typing Analytics & Speed Test Engine

A zero-dependency, offline-first, commercial-grade typing matrix system

☀️ Light Mode
<img width="1918" height="981" alt="Screenshot 2026-06-13 190223" src="https://github.com/user-attachments/assets/24550e9a-fca1-421d-a477-b4bebaaf355f" />
🌙 Dark Mode
<img width="1919" height="1004" alt="Screenshot 2026-06-13 190109" src="https://github.com/user-attachments/assets/af152aca-452f-43b3-9372-b2d1dd21d571" />
  Result
<img width="1919" height="984" alt="Screenshot 2026-06-13 190243" src="https://github.com/user-attachments/assets/153c8392-3f6e-496e-938e-ed2946f8ed94" />



TypeForge is a standalone, production-level typing analytics engine engineered specifically for high-performance front-end portfolios. Built with pure HTML, CSS, and Vanilla JavaScript, it runs entirely offline while delivering precision-grade diagnostics, real-time feedback, and hardened anti-cheat controls.

No frameworks. No APIs. No build tools. Just engineering.

🚀 Core Capabilities
🧠 Typing Engine (Low-Latency Core)
Atomic Real-Time Detection
Character-by-character evaluation using indexed string matrices and deterministic array loops.
Visual Caret Intelligence
Correct input → Green highlight
Incorrect input → Red with soft warning feedback
Active index → Animated caret underline
Anti-Abuse & Cheat Shielding
Clipboard injection fully blocked (Copy / Paste / Select-All)
Context menu isolation
Programmatic input bypass prevention
📊 Advanced Typing Analytics
True Net WPM
Formula: (Total Characters ÷ 5) ÷ Time (minutes)
Gross CPM
Raw keystroke throughput measurement.
Live Accuracy Rating
Precision calculated dynamically against total input vs error count.
Extended Diagnostics
Error tracking
Backspace behavior logging
Retroactive correction detection
🎨 Premium UI / UX Architecture
Adaptive Theme Engine
☀️ Light Mode & 🌙 Dark Mode
Auto-persisted via localStorage
Instant toggle with zero reload cost
Fluid Motion System
Sub-second easing curves
Soft elevation cards
Linear gradient accent layers
Telemetry Virtual Keyboard
Real-time key-press visualization mapped to user input.
🛠️ Engineering Architecture (The Hard Work)
1️⃣ Zero-Asset Audio System (Web Audio API)

No external audio files. No base64 bloat.

Sound feedback is generated dynamically using native Web Audio API oscillators:

✅ Correct Keystroke
High-frequency sine wave with short envelope
❌ Incorrect Keystroke
Low-frequency triangle wave with dampened decay

This guarantees instant playback, zero asset loading, and full offline compatibility.

2️⃣ High-Density DOM Delta Diffing
Test text is pre-split into immutable .char-span nodes
During input:
Only targeted class tokens are mutated
No container rewrites
No layout thrashing

Result: 60 FPS performance even on low-power devices

3️⃣ Isolated State Engine

All runtime variables are encapsulated inside a single structured JavaScript closure:

Timers
Metrics
Error counters
User preferences
Configuration switches

This creates a single source of truth and guarantees predictable UI updates.

⚙️ Configuration Options
Feature	Type	Available Options
Difficulty Level	String Segment	Easy / Medium / Hard
Time Limit	Integer	30s / 60s / 120s
Audio Feedback	Boolean	On / Muted
Persistence Cache	Local Storage	Automatic session analytics
💻 Installation & Offline Deployment

TypeForge is fully offline-ready. No setup required.

Clone the Repository
git clone https://github.com/Mr-Nilarnab/typeforge-engine.git
Run Instantly
Locate index.html
Double-click the file
Open in any modern browser
(Chrome, Edge, Firefox, Safari)

✅ No internet
✅ No local server
✅ No compilation

📜 Credits

Lead Core Engineer & UI/UX Architect
Mr-Nilarnab

All system architecture, typing logic, analytics formulas, Web Audio synthesis, DOM optimization strategies, and UI design were engineered independently.

🔗 Repository

TypeForge GitHub Repository
