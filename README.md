# Pi Quest: A Ridiculously Circular Adventure

An interactive web-based game that teaches what Pi is, its history, how it's calculated, and the patterns hidden in its digits.

## Features

- **What IS Pi?** - Interactive circle visualization showing the circumference-to-diameter ratio
- **Time Machine** - Timeline of Pi's history from Babylon to 105 trillion digits, with trivia quiz
- **Squeeze It!** - Archimedes' polygon method: watch inscribed/circumscribed polygons converge on Pi
- **Dart Circus** - Monte Carlo simulation: throw darts to estimate Pi
- **Formula Race** - Watch Leibniz, Nilakantha, Machin, and Chudnovsky formulas race to converge, with a deep dive into the Chudnovsky algorithm
- **Digit Detective** - Search for patterns in Pi's digits (computed dynamically up to 1M), explore the Feynman Point, analyze digit frequency
- **Memory Dojo** - Memorize and recall digits of Pi

## Run it

**https://pbaer.github.io/pi-quest**

### Locally

Serve the file with any static HTTP server:

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000/.