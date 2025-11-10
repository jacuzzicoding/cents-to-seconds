# Cents to Seconds - Money Timer

## Project Overview
A single-page web application that visualizes earnings in real-time based on hourly wage. Users input their hourly rate, start a stopwatch, and watch their money accumulate second-by-second.

## Tech Stack
- Pure HTML5/CSS3/JavaScript (no frameworks or dependencies)
- Single file: `index.html` (self-contained)
- Runs entirely in the browser, no build process needed

## How to Use
1. Open `index.html` in any modern web browser
2. Enter hourly wage in the input field
3. Click "Start" to begin the timer
4. Watch earnings accumulate in real-time
5. Use "Stop" to pause, "Reset" to restart

## File Structure
```
.
├── index.html          # Main application (HTML/CSS/JS all-in-one)
├── README.md           # Project description
├── LICENSE             # License file
└── CLAUDE.md          # This file
```

## Key Features
- Real-time money calculation: `(hourlyWage × elapsedTime) / 3600`
- Updates every 100ms for smooth animation
- Statistics panel showing per-second, per-minute, per-hour earnings
- Responsive design (mobile-friendly)
- Purple gradient background with green money display

## Development Notes
- No external dependencies or package managers required
- All styling is embedded in the HTML file for portability
- Timer precision: 100ms intervals for balance between accuracy and performance
- Wage input disabled during timer operation to prevent calculation errors

## Branch Convention
- Development branches: `claude/[feature-name]-[session-id]`
- Always push to the specified branch in the task description

## Future Enhancement Ideas
- Add currency selector (USD, EUR, GBP, etc.)
- Dark mode toggle
- Save wage to localStorage
- Session history/logging
- Export earnings data
- Sound effects on milestones
- Customizable themes
- Daily/weekly/monthly earnings projections
