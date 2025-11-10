# Cents to Seconds - Money Timer

A simple, elegant web application that visualizes your earnings in real-time based on your hourly wage. Enter your hourly rate, start the stopwatch, and watch your money accumulate second-by-second!

## Features

- **Real-time Money Calculation**: Watch your earnings accumulate as you work
- **Precise Timer**: Updates every 100ms for smooth animation
- **Statistics Panel**: See your earnings broken down per-second, per-minute, and per-hour
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Zero Dependencies**: Pure HTML5/CSS3/JavaScript—no frameworks or build process needed
- **Beautiful UI**: Purple gradient background with green money display

## How to Use

1. Open `index.html` in any modern web browser
2. Enter your hourly wage in the input field
3. Click "Start" to begin the timer
4. Watch your earnings accumulate in real-time
5. Use "Stop" to pause or "Reset" to restart

## Tech Stack

- **Pure HTML5/CSS3/JavaScript** (no frameworks or dependencies)
- Single self-contained file: `index.html`
- Runs entirely in the browser, no build process needed
- No external dependencies or package managers required

## File Structure

```
.
├── index.html          # Main application (HTML/CSS/JS all-in-one)
├── README.md           # Project description
├── LICENSE             # License file
└── CLAUDE.md          # Developer documentation
```

## How It Works

The app calculates your earnings using this formula:

```
Earnings = (Hourly Wage × Elapsed Time) / 3600
```

The timer updates every 100ms, balancing accuracy with smooth performance. The wage input is disabled during timer operation to prevent calculation errors.

## Future Enhancement Ideas

- Add currency selector (USD, EUR, GBP, etc.)
- Dark mode toggle
- Save wage to localStorage for persistence
- Session history and logging
- Export earnings data
- Sound effects on milestones
- Customizable themes
- Daily/weekly/monthly earnings projections
