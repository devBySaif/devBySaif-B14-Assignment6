# FitLog

FitLog is a workout library and daily training log for planning gym sessions. Explore exercises, review movement details, save workouts for later, and track the lifts you complete.

## Technologies

- Next.js App Router
- React 19 and TypeScript
- Tailwind CSS 4 with custom responsive CSS
- Lucide React
- FitLog REST API
- Browser `localStorage` for saved workouts and daily plans

## Key Features

1. **Workout library:** Browse exercises loaded from the FitLog API.
2. **Workout details:** View equipment, target muscle groups, difficulty, sets, reps, duration, calories, ratings, and step-by-step instructions.
3. **Daily training plan:** Add up to five workouts and track total exercises, duration, and calories.
4. **Saved workouts:** Keep a separate list of movements to revisit later.
5. **Progress tracking:** Mark planned workouts complete; plans, saved workouts, and completion state persist across reloads.

## Getting Started

### Requirements

- Node.js 20.9 or later
- npm

### Run locally

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### Other commands

```bash
npm run lint
npm run build
npm start
```

## API

- Workout library: [https://api.api-store.workers.dev/api/fitlog](https://api.api-store.workers.dev/api/fitlog)
- Single workout: `https://api.api-store.workers.dev/api/fitlog/:id`
