# ASCII Art Web - Premium Edition

A high-performance Go web application that takes string inputs and transforms them into stunning ASCII art using different font banners.

## Features

- **Text to ASCII:** Convert any ASCII-printable text into stylistic ASCII art.
- **Multiple Banner Styles:** Choose smoothly between `standard`, `shadow`, or `thinkertoy` fonts.
- **Responsive Design:** Completely usable and beautiful on mobile phones and desktop displays alike.
- **Error Handling:** Graceful error catching with custom 400 and 500 error pages.

## Technologies Used

- **Go (Golang):** Core backend server logic, routing, and ASCII transformation algorithms handling Windows/Linux file formatting (CRLF / LF) discrepancies securely.
- **Vanilla CSS:** Extreme UI styling, implementing modern aesthetics without heavy frameworks.
- **HTML / Vanilla JS:** Template rendering and lightweight interactive script for clipboard access.

## Installation and execution

1. Make sure you have Go installed on your machine.
2. Clone this repository.
3. Start the server from the root directory:
   ```bash
   go run .
   ```
4. Open your favorite modern web browser and navigate to:
   ```
   http://localhost:8080 or http://127.0.0.1:8080
   ```

## Usage

- Type your desired text into the specific input box (only standard ASCII characters from 32 to 126 are allowed).
- Open the visual select menu to change your text filter/banner.
- Click on "**GENERATE ASCII ART**".
- Use the quick "Copy" board to add your new digital art continuously to your clipboard.

## Error Behavior

Non-ASCII characters will result in a sleek custom graphical 400 error page reminding you to input valid English alphabet symbols. Any missing endpoints safely redirect you back or handle 404 intelligently.

---

