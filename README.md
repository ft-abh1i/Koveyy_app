# LEVEL UP — Personal Growth PWA (v2)

Mobile-first personal growth app with local-only storage.

## Included
- Five daily habits: communication, French, C + DSA, calisthenics, running
- XP points, eight levels, and seven achievement badges
- Suggested daily planner
- Focus timer and accumulated focus minutes
- Communication lab with speaking prompts, a 2-minute timer, confidence rating, and practice history
- Workout logging with activity type, duration, optional running distance, and notes
- Journal with mood, prompts, edit/delete, and history
- Streaks, weekly chart, skill practice totals, and weekly insight
- Configurable daily reminder preference, test notification, and reminder toggle
- JSON export and import/restore
- Persistent light/dark theme
- PWA manifest, icon, and offline service-worker caching

## Run locally
PWA installation and service workers require localhost or HTTPS:
1. Extract the ZIP.
2. In the folder, run `python -m http.server 8000`
3. Open `http://localhost:8000`.

## Install on Android
Deploy the folder to an HTTPS static host, open the URL in Chrome, then choose **Install app** or **Add to Home screen** from the browser menu.

## Data and notification limitations
Progress is saved in this browser's localStorage and is not synced across devices. Clearing browser site data may erase it; export JSON backups regularly. Imported backups replace current local data after confirmation. Browser notifications are best-effort and generally cannot guarantee scheduled delivery when the app is closed; reliable push notifications need additional infrastructure. Timer is most reliable while the app stays open.
