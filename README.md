# Frigates
# explore-the-world
Frigates is a unique, visually immersive search homepage that combines a fully functional web search interface with an animated naval battle scene. It’s designed to be a fun, thematic starting point for your browsing – with warships, missiles, and a cosmic backdrop, all while letting you search the web via DuckDuckGo.

# ✨ Features
🎯 Full‑featured search bar – with category selection (All, Images, Videos, News, Maps) powered by DuckDuckGo.

⚡ I’m Feeling Lucky – instantly searches a random naval‑themed query.

🎤 Voice & Image search buttons – demo‑ready placeholders for future integration.

🌊 Animated background – a real‑time canvas rendering of:

🌟 Twinkling stars and drifting clouds.

⚓ Detailed warships with smoke, radar, and blinking lights.

🚀 Missiles launching and homing in on targets.

💥 Distant explosions and ocean wave effects.

📱 Fully responsive – works seamlessly on desktop, tablet, and mobile.

⌨️ Keyboard shortcut – press / to focus the search bar instantly.

🌐 Global stats – footer shows "7 seas covered", "190+ nations", "0.3s response".

🚀 Getting Started
You don’t need to install anything – just open the index.html file in any modern web browser.

Quick start
Clone or download this repository.

Open index.html in your browser.

Start searching – or just enjoy the naval battle!

Alternatively, you can host it on any static hosting service (GitHub Pages, Netlify, Vercel, etc.) and share it with the world.

🧭 How to use
Search: Type your query, choose a category (All, Images, Videos, News, Maps), and click Search or press Enter.

“I’m Feeling Lucky”: Click the ✨ button to search a random topic like "naval history" or "ocean exploration".

Voice / Image: Click the mic or camera buttons for demo alerts – you can connect them to real APIs.

Keyboard shortcut: Press / anywhere on the page to jump to the search input.

🛠️ Technologies
HTML5 – structure and content.

CSS3 – modern styling with glass‑morphism, gradients, and full responsiveness.

JavaScript (ES6) – powers the entire animated canvas scene and search logic.

Canvas API – for real‑time rendering of ships, missiles, waves, stars, and clouds.

DuckDuckGo – used as the search backend (privacy‑focused, global results).

📁 File structure
text
frigates/
├── index.html          # The complete single‑page application
└── README.md           # This file
No external dependencies, images, or libraries are required – everything is self‑contained.

🎨 Customisation
You can easily modify the theme or behaviour:

Change the search engine: Edit the base URL in the getSearchUrl() function.

Add more categories: Extend the <select> options and update the getSearchUrl() logic.

Adjust the battle scene: Tweak NUM, MAX_SPEED, CONNECT_RADIUS, or ship colours in the JavaScript.

Change quick links: Update the <div class="quick-links"> with your own topics.

Replace footer stats: Modify the <div class="footer-stats"> content.

📱 Responsive breakdown
Device	Behaviour
Desktop	Full‑size header, wide search bar, and detailed canvas.
Tablet	Slightly smaller fonts, compact layout, and still usable.
Mobile	Top navigation collapses, search box stacks vertically, and canvas scales down.
🤝 Contributing
Contributions are welcome! If you have ideas to improve the scene, add new search providers, or enhance accessibility, feel free to open an issue or submit a pull request.

Fork the repository.

Create your feature branch (git checkout -b feature/amazing-feature).

Commit your changes (git commit -m 'Add some amazing feature').

Push to the branch (git push origin feature/amazing-feature).

Open a Pull Request.

📄 License
This project is open‑source and available under the MIT License.
Feel free to use, modify, and distribute it as you like.

🌟 Acknowledgements
Built with ❤️ by frigates.

Inspired by the beauty of the open sea and the thrill of exploration.

Made for the curious minds who love to explore – both the web and the unknown.

