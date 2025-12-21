Interactive Glassmorphism Control Card UI
📌 Project Overview

This project is a highly interactive, glassmorphism-styled UI card built using pure HTML and CSS.
It demonstrates advanced front-end techniques such as:

Glassmorphism UI design

Direction-based hover interactions

CSS-only state management using radio inputs

Animated glow, glitch, and depth effects

3D transforms with perspective

Accessibility-aware markup (ARIA roles)

The component simulates an “Add Additional Requests” control panel, where users can increment or decrement a request count (0–2) with visually rich feedback.

🎯 Key Features
1. Glassmorphism Design

Semi-transparent background

Backdrop blur effects

Subtle noise texture overlay

Depth illusion using translateZ

2. Directional Hover Interaction

Card reacts differently when hovered from:

Top-Left

Top-Right

Bottom-Left

Bottom-Right

Creates a premium, tactile UI experience

3. CSS-Only State Management

Uses hidden radio inputs (count-0, count-1, count-2)

No JavaScript required for:

Count switching

Button enable/disable states

UI transitions

4. Animated Glow & Glitch Effects

Multi-color glow layers (Purple, Pink, Teal)

Pulse animation for glow

Glitch animation when request limit is reached

Edge glitch effect at max state

5. Interactive Counter Control

Increment (+) and decrement (−) buttons

Disabled states at min/max limits

Real-time visual feedback

Count displayed using CSS counters

6. Accessibility Considerations

ARIA roles for screen readers

Logical grouping of controls

Non-interactive decorative elements marked as aria-hidden

🧩 File Structure
project-root/
│
├── index.html        # Main HTML structure
├── style.css         # Complete styling & animations
└── README.md         # Project documentation

🛠️ Technologies Used

HTML5

Semantic elements

ARIA attributes for accessibility

CSS3

CSS Variables

Grid & Flexbox

3D Transforms (perspective, translateZ)

Keyframe animations

Radial gradients

Mix-blend modes

❌ No JavaScript frameworks
❌ No external libraries
✅ 100% Vanilla HTML & CSS

⚙️ How It Works (Logic Explanation)
Request Counter Logic

Three hidden radio inputs represent states:

count-0 → 0 requests

count-1 → 1 request

count-2 → 2 requests

Buttons are <label> elements linked to radio inputs

CSS sibling selectors (~) control:

Which buttons appear

Which value is displayed

Which animations are active

Limit Reached State

When count-2 is selected:

“Request limit reached” message appears

Subtitle hides

Glitch animations activate

Increment button is disabled

Directional Hover Logic

Four transparent overlay divs detect hover direction

Based on hover area:

Card shifts position

Glow moves dynamically

Noise layer tilts in 3D space

🎨 UI & Animation Highlights

Glow Pulse Animation
Creates a living, breathing card effect.

Glitch Text & Edge Animations
Activates when maximum request count is reached.

Depth Transitions
Hovering raises elements in Z-axis for realism.

📱 Responsiveness

Uses flexible units (em, %)

Card remains centered and adaptive

Optimized for modern desktop viewports

Note: Mobile support can be added by adjusting hover logic for touch devices.

🚀 Use Cases

This UI pattern is suitable for:

SaaS dashboards

Pricing plans

Subscription add-ons

Feature limit controls

Portfolio UI showcases

Advanced CSS practice projects

📌 Customization Tips

You can easily customize:

Card size → --card-width

Glow colors → --accent-*

Blur strength → backdrop-filter

Maximum count → add more radio inputs

Animations → tweak keyframes

📄 License

This project is open-source and free to use for learning, portfolio, and personal projects.
For commercial use, attribution is appreciated.

👨‍💻 Author

Sachin Yadav
Front-End / Web Developer
Focused on modern UI, CSS mastery, and interactive web experiences.
