MY WATCHLIST — UPDATE GUIDE

Upload these five files to the root of your GitHub Pages repository, replacing existing files:
index.html
manifest.webmanifest
service-worker.js
icon.svg
README.txt

Features:
- All / Recently added / Movies / Series / Anime / Watched / Smart picks
- Watched items stay in their type category and sort below unwatched items
- Edit title, type, genre, language, description, and tags
- Search online for a title's details
- Ask AI button opens ChatGPT with a title-specific prompt (internet and ChatGPT access required; not an embedded AI API)
- Optional poster image URL field; paste a direct image URL to show a poster
- Smart picks based on saved genres and languages
- Export/import JSON backups
- Local device storage and service-worker caching

After uploading, commit changes and refresh the live site. If the installed app shows the old version, close it, open the website in Chrome, refresh, and reopen the app.

Smart picks are rule-based recommendations, not a connected generative-AI model. Research buttons open online search results. Descriptions can be added/edited manually. Each device keeps its own list/progress unless a sync backend is added.

AI note: The Ask AI button opens ChatGPT in a new tab; it does not run an AI model inside the app. Poster URLs must be added manually in this version.

Extra personalisation:
- Favourites tab and favourite toggle
- Optional personal rating from 1 to 5 stars
- Accent colour options and sorting by title, newest, rating, or unwatched first
- AI helper opens ChatGPT with a tailored prompt; it is not an embedded API connection
- Poster image URL field; paste a direct image URL to show a poster
