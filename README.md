## Odliczanie Czasu (Countdown Timer)

### Overview

The "Odliczanie Czasu" project is a simple yet elegant countdown timer that displays the current date and time, updating every second. The design is clean and modern, making use of large, bold typography and a visually appealing color scheme. This project serves as a great example of using JavaScript for real-time data updates and CSS for styling.

### Features

- **Real-Time Clock:** Displays the current date and time, updating every second.
- **Responsive Design:** The timer is styled to be centered on the screen and scales well across different screen sizes.
- **Customizable:** Easy to modify the design elements and functionality to suit specific needs.

### Technologies Used

- **HTML:** Provides the basic structure of the web page.
- **CSS:** Used for styling the countdown timer, including fonts, colors, and layout.
- **JavaScript:** Implements the countdown functionality, updating the displayed time every second.

### File Structure

- `index.html`: The main HTML file that includes the structure and links to CSS and JavaScript files.
- `style.css`: The CSS file responsible for styling the countdown timer.
- `script.js`: The JavaScript file that contains the logic for updating the time.

### How to Use

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/odliczanie-czasu.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd odliczanie-czasu
   ```
3. **Open `index.html` in a web browser:**
   ```bash
   open index.html
   ```

### Key Sections

- **HTML Structure:** The page consists of a single `div` with the ID `zegar`, which is used to display the time.
- **CSS Styling:** 
  - The font "Bebas Neue" is used for a bold and clean look.
  - The clock is centered on the screen with a prominent red background and white text.
  - A shadow effect is applied to the text for added depth.

### JavaScript Functionality

- **`odliczanie()` Function:** This function calculates the current date and time, formats it, and displays it inside the `zegar` div. It uses `setTimeout` to call itself every second, ensuring that the displayed time is always accurate.
