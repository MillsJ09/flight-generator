# Flight Generator

A simple web-based flight route generator that allows users to input a starting airport ICAO code and select an aircraft type. It then displays up to 50 possible destination airports suitable for the aircraft's range from the departure airport, along with estimated distances and flight durations.

## Features

- Input a departure airport ICAO code.
- Select an aircraft type with predefined ranges and speeds.
- Optional filtering by airline (future feature).
- Generates a randomized list of up to 50 destination airports within range.
- Displays results in a table with:
  - Departure ICAO
  - Arrival ICAO
  - Distance (nautical miles)
  - Estimated flight time
  - Aircraft type
- Sort results by flight duration (planned).
- Light/dark mode toggle with sun/moon icon.
- Uses Museo Sans font for modern, clean typography.

## How to Use

1. Open `flight-generator.html` in any modern web browser.
2. Enter a valid departure airport ICAO code (e.g., `EGJB`).
3. Select an aircraft type.
4. Click **Generate Flights**.
5. View the generated flight list in the table below.
6. Toggle light/dark mode using the sun/moon icon in the top right corner.

## Installation

No installation required. Simply download the `flight-generator.html` file and open it in your browser.

## Deployment

For hosting online, you can:

- Upload to a GitHub repository and enable GitHub Pages.
- Use free hosting services like Netlify or Vercel.
- Host on your own web server.

## Notes

- Destination airports are randomly selected from a predefined list and may not represent real-world viable routes.
- Future improvements include adding airline filtering and sorting options.

## License

This project is open source and free to use.

---

Feel free to contribute or request features!
