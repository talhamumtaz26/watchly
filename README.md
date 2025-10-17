# Watchly

**Watchly** is a modern React Native app that lets you browse, track, and organize movies and TV series using the **TMDb API**.  
It shows details for each title, upcoming releases, and lets you mark items as *Watch Later* or *Watched*. The app also tracks your total watch time.

---

## Features
- Browse popular, top-rated, and upcoming movies.
- Search for any movie or series.
- Add titles to **Watch Later** or mark as **Watched**.
- Track **total watch time** from your watched list.
- Clean dark UI with a cinematic feel.

---

## Tech Stack
React Native (Expo) · TMDb API · Axios · AsyncStorage · React Navigation

---

## Setup
```bash
git clone https://github.com/yourusername/watchly.git
cd watchly
npm install
npx expo start

Add your TMDb API key in api.js:

const API_KEY = "YOUR_TMDB_KEY";
