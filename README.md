A responsive, vanilla JS calculator that performs basic arithmetic with keyboard support, input validation, and a clean UI. Built using semantic HTML, modern CSS, and modular JavaScript.

Features
Basic operations: addition, subtraction, multiplication, division

Percentage, toggle sign, decimal input, and clear/reset

Keyboard support for digits, operators, Enter, Backspace, and Escape

Expression-safe evaluation (no eval), precise float handling, and input sanitization

Responsive layout with accessible roles/labels and focus states

LocalStorage toggle for theme (light/dark)

Live demo
Add GitHub Pages link here after enabling Pages in repository settings.

Tech stack
HTML5 for structure and accessibility (aria-labels, role=button)

CSS3 for responsive grid layout and theming (CSS variables)

JavaScript (ES6 modules) for state management and operations

Getting started
Clone: git clone https://github.com/USERNAME/calculator.git

Open index.html in a browser (or use a simple local server).

Optional: npm i -g serve and run serve . then open the shown URL.

Usage
Click buttons or use keyboard:

Digits: 0–9

Operators: + - * /

Enter/Return = equals, Backspace = delete, Escape = clear

Use % for percentage and +/- to toggle sign.

Project structure
index.html — markup and ARIA

styles.css — variables, layout, themes

js/

app.js — event wiring, controller

state.js — calculator state, finite state logic

ops.js — math operations and precision helpers

keys.js — keyboard mapping

Implementation details
Finite state machine to handle chaining operations and edge cases

Floating-point safety via fixed precision rounding

Graceful errors: divide-by-zero guard and display messages

Accessibility: tab navigation, aria-pressed, screen-reader labels

Roadmap
Memory functions (MC/MR/M+/M-)

Scientific mode (sin, cos, tan, pow, sqrt)

History tape with undo/redo

i18n for decimal separators

Contributing
Issues and PRs are welcome. Please describe changes and add concise test cases.

License
MIT

Tip: Replace USERNAME with the actual handle, add screenshots (assets/screenshot.png), and include a short GIF in the README for better engagement.
