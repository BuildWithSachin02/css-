💬 CSS-Only Interactive Dialogue System

A fully interactive branching conversation UI built using pure HTML and CSS only — no JavaScript involved.
This project demonstrates how complex user interactions, dialogue trees, and animated text can be achieved using radio buttons, labels, and advanced CSS selectors.

Inspired by retro game dialogue systems and experimental UI patterns.

✨ Key Features

✅ 100% HTML + CSS

❌ No JavaScript required

🎮 Game-style branching conversation system

🧠 Logic handled via:

Radio inputs

CSS :checked selectors

Sibling selectors (~)

⌨️ Typewriter-style animated text

🧍 Character expression changes (pixel face sprites)

🔁 Restartable conversation flow

🎨 Retro / pixel-art aesthetic

🛠️ Technologies Used

HTML5

Radio inputs as state holders

Labels as clickable options

Semantic structure

CSS3

Advanced selectors (:checked, ~)

CSS variables

Keyframe animations

Sprite switching via background-image

Step-based typing animation

📂 Project Structure
css-dialogue-system/
│
├── index.html
├── style.css
└── README.md

🧠 How It Works (Core Logic Explained)
1️⃣ State Management Using Radio Inputs

Each dialogue state is represented by a hidden radio input:

<input type="radio" name="s" id="r-0-1-0" class="s">


Only one radio can be checked at a time

This acts like a state machine

2️⃣ Navigation Using Labels

Each dialogue option is a <label> connected to a radio input:

<label for="r-0-1-0">What about mine?</label>


Clicking the label:

Changes the checked radio

Triggers new dialogue and options via CSS

3️⃣ Conditional Rendering via CSS

CSS checks which radio is selected and shows content accordingly:

#r-0-1:checked ~ .input .for-r-0-1 {
  display: flex;
}


This replaces JavaScript if / else logic entirely.

4️⃣ Animated Dialogue Text

Text appears with a typewriter effect using steps() animation:

animation: wahoo steps(var(--n)) backwards;


Each line calculates its own animation duration using CSS variables.

5️⃣ Character Expressions (Sprites)

The character face changes based on dialogue mood:

.sans {
  background-image: var(--disgruntled);
}


Expressions include:

Normal

Confused

Disgruntled

Wink

Pensive

UwU / OwO styles

All handled purely in CSS.

🔄 Restart Conversation

The conversation can be restarted using a special radio state:

<label for="def">&lt;Restart dialog&gt;</label>


This resets the entire flow without reloading the page.

🎯 Use Cases

Game dialogue systems

Interactive storytelling

Experimental UI demos

CSS logic practice

Portfolio showcase

Creative frontend challenges

🎨 Customization Ideas

You can easily:

Add new dialogue branches

Change character expressions

Adjust typing speed

Replace character sprites

Modify text tone or humor

🚀 How to Run

Clone or download the repository

Open index.html in any modern browser

Click dialogue options to explore different paths

No build tools or dependencies required.

👨‍💻 Author

Sachin Yadav
Frontend / Web Developer

Focus Areas:

HTML

CSS Animations

Creative UI

Logic without JavaScript

📄 License

This project is open-source and free to use for:

Learning

Personal projects

Portfolio demos

Attribution appreciated but not required.

⭐ If you found this interesting, consider starring the repository on GitHub.
