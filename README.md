# 💌 Compliment Generator

A charming, card-based web application designed to spread kindness and positivity. This single-page app mimics the experience of drawing from a deck of cards, presenting the user with a randomized compliment through smooth animations and a warm, inviting aesthetic.

---

## 🌟 Features

* **Warm & Loving Aesthetic:** A sunset-inspired gradient background with animated decorative orbs.
* **Heartbeat Animation:** A custom SVG heart loader that pulses while "gathering affection" to build anticipation.
* **Tactile UI:** Interactive card-hover effects and responsive buttons that make the interface feel alive.
* **One-Click Sharing:** Built-in "Copy for a Friend" functionality with instant visual feedback.
* **Mobile Optimized:** Fully responsive design that works beautifully on desktops, tablets, and smartphones.

---

## 🛠️ Tech Stack

* **HTML5:** Semantic structure for the card layout and action buttons.
* **CSS3:** Custom properties (variables), Flexbox, and keyframe animations for the background and heart pulse.
* **Vanilla JavaScript:** Logic for randomization, state management (loading delays), and Clipboard API integration.
* **Google Fonts:** Utilizes *Lato* for structural text and *Nunito* for high-impact, bold compliments.

---

## 🚀 Getting Started

### 1. Prerequisites
This is a purely client-side application. No servers, compilers, or build tools are required.

### 2. Installation
1.  Copy the code into a file named `index.html`.
2.  *(Optional)* Place a `favicon.png` in the root directory to customize the browser tab icon.

### 3. Usage
Simply open `index.html` in any modern web browser. 

---

## 🎨 Customization

You can easily tailor the experience to your needs:

* **Edit Compliments:** Locate the `compliments` array in the `<script>` section to add or remove messages.
* **Adjust Timing:** Change the `setTimeout` value in the `fetchNewCompliment` function to make the "gathering" phase faster or slower.
* **Theme Colors:** Modify the CSS `:root` variables at the top of the style tag to change the primary red and ivory color scheme.

---

## 📁 Project Structure

```text
├── index.html         # Contains all HTML, CSS, and JavaScript
└── favicon.png        # (Optional) Browser icon