# 🚁 Drone Delivery Animation

A fun and interactive drone delivery animation built using HTML, CSS, and JavaScript.
This project visually simulates a drone taking off, delivering a package, and returning, all triggered by a simple click.

# 📋 Table of Contents

- Overview

- Features

- Demo

- Installation

- Usage

- Project Structure

- How It Works

- Customization

- Technologies Used

- Troubleshooting

- License

# 🧭 Overview

This animation showcases a drone delivery workflow through a smooth sequence of CSS transitions and SVG graphics.
When you click the main button area, a drone takes off, moves across the screen, drops a package, and returns — with synchronized text updates like “Processing,” “Delivering,” and “Delivered.”

The visual and motion effects are entirely done with CSS animations triggered by JavaScript class toggles.

# ✨ Features

🎬 Interactive one-click drone animation

🕒 Smooth transitions with timing and sequencing

📦 SVG-based animated drone and package

💬 Dynamic text updates (Processing → Delivering → Delivered)

🎨 Fully customizable colors and motion parameters

🔁 Automatic reset after animation completes

🎥 Demo

Click the container to trigger the animation sequence.

You can view the animation locally or host it on any static server (e.g., GitHub Pages, Netlify).

# ⚙️ Installation

Clone the repository:

git clone https://github.com/yourusername/drone-delivery-animation.git

cd drone-delivery-animation



Open the project:

Simply open index.html in your web browser.

(No build steps or dependencies are required — it’s pure HTML/CSS/JS.)

# 🧠 Usage

Open the index.html file in a browser.

Click on the blue demo box.

Watch the animation sequence play out:

Checkout → Processing → Delivering → It’s on the way → Delivered

After ~10 seconds, it automatically resets for the next click.

# 🗂️ Project Structure
drone-delivery-animation/
├── index.html        # Main HTML file containing the SVG and structure\
├── style.css         # Contains all animations, transitions, and styling\
└── script.js         # Handles click events and timing control\


# ⚡ How It Works
JavaScript (script.js)

Listens for a click on .demo

Adds/removes classes (s--processing, s--reverting) to control animation states

Uses a timeout to reset animation after 10 seconds

CSS (style.css)

Defines transitions for the drone, package, text, and progress circle

Controls keyframes for flight paths (tiltAnim, grabAnim, revertAnim)

Manages text and dot animations for step-by-step visual feedback

HTML (index.html)

Contains the SVG structure for the drone

Includes multiple text steps and circular progress visuals

# 🎨 Customization

You can modify:

Colors: Edit variables like #61d4f1, #53e2c2, and #ecb400 in style.css

Timing: Adjust transition durations and delays in CSS

Text: Edit labels such as “Delivering” or “Delivered” in index.html

# 🧩 Technologies Used

HTML5

CSS3 (Keyframes, Transitions, SVG Styling)

Vanilla JavaScript (ES6)

No frameworks or external libraries required.

# 🐞 Troubleshooting
Issue	Cause	Solution
Animation doesn’t trigger	JavaScript not loaded	Ensure script.js is linked correctly
Animation too fast/slow	Timing mismatch	Adjust transition delays in style.css
Drone not visible	SVG not rendering	Check browser compatibility or scaling settings

# 📜 License

This project is released under the MIT License — feel free to use, modify, and distribute it.
