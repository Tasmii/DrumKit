# Drum Kit Project

## Overview

This project creates a simple interactive Drum Kit using HTML, CSS, and JavaScript. The Drum Kit allows users to play different drum sounds by clicking on buttons or pressing corresponding keys on the keyboard.

## Features

- Seven drum sounds that can be played using buttons or keyboard keys (`w`, `a`, `s`, `d`, `j`, `k`, `l`).
- Visual feedback for button presses.
- Custom styles for the drum kit interface.

## Technologies Used

- HTML
- CSS
- JavaScript

## Setup Instructions

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/drum-kit.git
   ```
2. **Navigate to the Project Directory:**
   ```bash
   cd drum-kit
   ```
3. **Open `index.html` in Your Browser:**
   You can simply open the `index.html` file in any web browser to view and use the Drum Kit.

## Usage

- **Clicking on Buttons:**
  Click any of the buttons labeled `w`, `a`, `s`, `d`, `j`, `k`, or `l` to play the corresponding drum sound.
  
- **Using Keyboard Keys:**
  Press any of the keys `w`, `a`, `s`, `d`, `j`, `k`, or `l` on your keyboard to play the corresponding drum sound.

## Customization

- **Changing Sounds:**
  To change the drum sounds, replace the files in the `sounds` directory with your own `.mp3` files, ensuring they have the same names as the original files.

- **Changing Button Images:**
  To change the button images, replace the files in the `images` directory with your own `.png` images, ensuring they have the same names as the original files.

- **Styling:**
  Modify the `styles.css` file to change the appearance of the Drum Kit. You can adjust colors, fonts, sizes, and other CSS properties as desired.

## Code Explanation

### HTML (`index.html`)

- The HTML file defines the structure of the Drum Kit, including the title, buttons, and footer.

### CSS (`styles.css`)

- The CSS file provides styling for the Drum Kit, including the background color, button styles, fonts, and animations.

### JavaScript (`index.js`)

- The JavaScript file adds functionality to the Drum Kit. It includes event listeners for button clicks and key presses, plays the corresponding sounds, and adds visual feedback for button presses.

#### Key Functions:

- **makeSound(key):** Plays the corresponding drum sound based on the key pressed.
- **buttonAnimation(currentKey):** Adds and removes the 'pressed' class to the active button for visual feedback.

## Live Demo

The project is deployed and can be accessed [here](https://tasmii.github.io/DrumKit/).

## Author

- **Tasmiya Ilahi**
- [GitHub](https://github.com/Tasmii)
