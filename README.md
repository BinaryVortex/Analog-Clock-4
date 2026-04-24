# Analog Clock

Simple, elegant analog clock built with HTML, CSS and JavaScript.

> Analog Clock Built Using HTML, CSS and JavaScript.


![Analog Clock Screenshot](https://raw.githubusercontent.com/BinaryVortex/Analog-Clock-4/main/Screenshot%202024-10-13%20200258.png)

## Overview

A minimal, dependency-free analog clock using CSS for styling and JavaScript for live time updates. Hands move smoothly and the design is responsive for use in modern browsers.

## Features

- Clean, minimal design
- Smooth second, minute, and hour hands
- No external libraries or build tools
- Small, easy-to-read codebase: index.html, style.css, script.js

## Files

- `index.html` — markup for the clock  
- `style.css` — styling and layout  
- `script.js` — logic that updates the clock hands every second  
- `Screenshot 2024-10-13 200258.png` — demo screenshot used above

## Quick start

1. Clone the repository:

   git clone https://github.com/BinaryVortex/Analog-Clock-4.git

2. Open the project:

   - Option A — Open the `index.html` file directly in your browser (double-click).  
   - Option B — Serve locally (recommended for consistent behavior):

     python -m http.server 8000
     # then open http://localhost:8000

## Customization

- Styling (colors, sizes, effects) is controlled in `style.css`. Tweak variables or rule values to change appearance.  
- Update motion behavior (e.g., smooth vs stepped second hand) in `script.js`. The clock logic is straightforward and well-commented for easy edits.

## Contributing

Contributions, issues, and feature requests are welcome.

- Open an issue to report bugs or suggest features.
- Send a pull request with improvements, fixes, or alternative styles.

Please keep changes small and focused; add comments explaining non-trivial JavaScript behavior.

## Live demo (optional)

You can publish the repo via GitHub Pages:

1. Go to the repository Settings → Pages
2. Choose the `main` branch and root (`/`) as the source
3. Save and open the provided site URL

## License

No license file included. If you want this to be reusable by others, consider adding an open-source license such as MIT (I can add one for you if you want).
