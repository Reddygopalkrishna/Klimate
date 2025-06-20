# Whether App

A modern weather dashboard built with React, TypeScript, Vite, and Tailwind CSS. It allows users to search for cities, view current weather, forecasts, and manage favorite locations.

---

## Features

- Search for any city and view current weather
- 5-day weather forecast
- Add/remove favorite cities
- Responsive, modern UI with dark/light theme toggle
- Local storage for favorites and search history

---

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Reddygopalkrishna/Klimate.git

cd whether-app
```

### 2. Install dependencies

```bash
npm install
# or
yarn
```

### 3. Create a `.env` file

Create a `.env` file in the root directory and add your OpenWeatherMap API key:

```
VITE_OPENWEATHER_API_KEY=your_openweathermap_api_key
```

### 4. Start the development server

```bash
npm run dev


Visit the local URL shown in your terminal (usually http://localhost:5173).

---

## Project Structure

- `src/` - Main source code
  - `components/` - UI and feature components
  - `api/` - API configuration and calls
  - `hooks/` - Custom React hooks
  - `pages/` - Main app pages
  - `context/` - Theme and global state providers
- `public/` - Static assets
- `.env` - Environment variables (not committed)

---

## Environment Variables

- `VITE_OPENWEATHER_API_KEY` - Your OpenWeatherMap API key

---

