🎟️ Digital Pass / Animated Ticket UI (HTML & CSS)

A premium Digital Pass / Ticket UI animation built using pure HTML & CSS.
This project showcases a floating, flipping ticket card with modern gradients, reflections, QR code styling, barcode effects, and smooth animations — ideal for event passes, result cards, confirmations, or portfolio UI demos.

✨ Features

Pure HTML5 + CSS3 (No JavaScript required)

Smooth floating ticket animation

3D flip effect (front ↔ back on hover)

Animated:

Gradient glow bar

Floating motion

Ticket entry motion

Icon cube micro-animations

QR code breathing effect

Realistic ticket design:

Barcode effect

QR code placeholder

Perforated ticket edge

Light reflex animation

Fully responsive & modern UI

🛠️ Technologies Used

HTML5

Semantic layout

SVG icons

Embedded QR image

CSS3

Flexbox

3D transforms

Keyframe animations

Gradients & masks

Hover interactions

📂 Project Structure
digital-pass-ui/
│
├── index.html
├── style.css
└── README.md

🎥 Animation Breakdown
1️⃣ Ticket Movement

Ticket enters from top

Floats gently using @keyframes float

Final zoom-out exit animation

2️⃣ 3D Flip Effect

On hover, ticket flips using:

transform: rotateY(180deg);

3️⃣ Gradient Glow Bar

Conic gradient rotates continuously

Gives a premium neon UI feel

4️⃣ Ticket Details

Front side:

Event name

Ticket number

Small QR

Back side:

Date

Large QR code

Breathing border animation

🧠 How It Works (Logic Overview)

.ticket-mask → Controls visibility and perspective

.ticket-flip-container → Handles 3D rotation

.front / .back → Two sides of the ticket

backface-visibility: hidden → Prevents overlap

transform-style: preserve-3d → Enables depth

Keyframes handle:

Floating

Entry animation

Icon micro-motions

Glow rotation

▶️ How to Use

Download or clone the repository

Open index.html in your browser

Hover on the ticket to see the flip effect

To integrate into another project:

<link rel="stylesheet" href="style.css">


Paste the ticket HTML inside your page layout.

🎨 Customization Guide

You can easily customize:

Event name

Ticket number

Date

Colors & gradients

Animation speed

QR image

Example:

.ticket-body {
  width: 360px;
}

💡 Use Cases

Quiz result pass / certificate

Event ticket UI

Conference pass

Digital ID card

Portfolio animation showcase

Premium confirmation page

👨‍💻 Author

Sachin Yadav
Frontend / Web Developer

Skills Used

HTML

CSS Animations

UI/UX Design

Creative Interfaces

📄 License

This project is open-source and free to use for:

Learning

Portfolio projects

Personal & demo use

⭐ If you like this UI, don’t forget to star the repo on GitHub!





#output

https://github.com/user-attachments/assets/7592b94c-06a0-45ea-9aa4-561874d37da8

