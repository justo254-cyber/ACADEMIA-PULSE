🎓 ACADEMIA PULSE
Empowering minds through Interactive Learning.

Academia Pulse is a modern, web-based educational portal designed to provide students with an immersive learning environment. It integrates real-time simulations, interactive mathematical tools, and a gamified "Fun Zone" to make learning engaging and dynamic.

🚀 Features
1. Interactive Learning Modules
Access high-quality external simulations and tools directly within the dashboard:

Chemistry: Interactive Molecule Shapes (via PhET).

Biology: Natural Selection simulations.

Physics: DC Circuit construction kit.

Mathematics: Integrated GeoGebra Classic interface.

Geography: Virtual Science Labs via Merlot.

Physical Education: Curated workout and stretch routines.

2. Gamified Experience (Fun Zone)
Tic-Tac-Toe: A built-in mini-game where students can play against PulseBot, the platform's AI, featuring a simulated "matchmaking" countdown.

3. Smart Assistance
PulseBot: A contextual chat widget that provides instant guidance and directs users to relevant subject modules based on their queries.

Global Chat: A "Roblox-style" minimized chat interface for community interaction.

4. Modern UI/UX
Vanta.js Integration: Dynamic, animated "Net" background on entry pages.

Responsive Dashboard: A clean sidebar-based navigation system.

Custom Authentication: Clean Sign-Up and Sign-In flows tailored for Kenyan education systems (8-4-4 and CBC).

🛠️ Tech Stack
Frontend: HTML5, CSS3, JavaScript (ES6+).

Animations: Vanta.js & Three.js.

Integrations: * PhET Interactive Simulations (University of Colorado Boulder).

GeoGebra.

Merlot Virtual Labs.

📂 Project Structure
Plaintext
├── index.html          # Main entry point containing UI and Logic
├── Styles              # Embedded CSS for:
│   ├── Vanta Canvas    # Full-screen background
│   ├── Auth Cards      # Login/Signup styling
│   └── Sidebar/Content # Dashboard layout
└── Scripts             # Embedded JS for:
    ├── Navigation      # SPA-style page switching
    ├── Game Logic      # Tic-Tac-Toe AI and mechanics
    └── PulseBot        # Automated chat responses
⚙️ How to Use
Enter the Academy: Click "Enter Academy" on the landing page.

Authentication: Sign up with your details (School, System, County).

Explore: Use the sidebar to switch between Science simulations and Math tools.

Take a Break: Visit the Fun Zone to challenge PulseBot to a game.

Get Help: Use the PulseBot widget at the bottom right for navigation tips.

👥 Authors
Justus and Mark

Support: WhatsApp Contact

[!NOTE]
This project is designed as a frontend prototype. For production use, a backend (like Firebase or Node.js) is recommended to handle persistent user data and live global chat messaging.
