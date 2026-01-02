# vrchni

A single Hono.js index file that serves HTML on each route.

## Features

- Single file Hono.js server
- Serves HTML on `/route/*` pattern
- Clean, responsive HTML pages
- Easy to run and modify

## Installation

```bash
npm install
```

## Usage

Start the server:

```bash
npm start
```

For development with auto-reload:

```bash
npm run dev
```

The server will start on `http://localhost:3000` by default.

## Routes

- `/` - Home page with navigation
- `/route/*` - Any route under `/route/` will serve an HTML page
  - Example: `/route/home`
  - Example: `/route/about`
  - Example: `/route/anything-you-want`

## Environment Variables

- `PORT` - Server port (default: 3000)

## Example

Visit these URLs after starting the server:
- http://localhost:3000/
- http://localhost:3000/route/home
- http://localhost:3000/route/about
- http://localhost:3000/route/dashboard