# Book Log

Book Log is an extremely minimal book tracking app written in React.

## App design

- Everything is displayed in dark mode with the **Courier New** font.
- The main screen consists of two elements:
  1. **Book list** – a chronological list of books the user has read, with the most recent entry at the bottom.
  2. **Command input** – a terminal‑like bar at the bottom where the user types in a book name. When text is entered the app queries a books API to search for actual titles and lets the user add a result to the log.

## Development

The frontend React app lives in the `frontend` directory. After installing dependencies with `npm install`, run the development server with:

```bash
npm start
```

This uses `react-scripts` to serve the app on localhost.
