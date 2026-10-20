SOUNDSPACE — Interactive sound website

HOW TO OPEN
1. Extract the ZIP file (if you received the ZIP).
2. Open the soundspace_website folder.
3. Double-click index.html. It opens in Chrome.

FEATURES
- Responsive dashboard and sound library
- Search sounds and save favorites during the current session
- Browser-generated soundscapes using Web Audio API
- Tone generator with adjustable frequency and volume
- Live microphone frequency visualizer (requires microphone permission; best on localhost/HTTPS)
- No external libraries or backend required for this demo

NOTE
This is a complete front-end demo that opens directly in Chrome. Favorites are session-only, and there is no server/database login yet. Microphone access can be restricted when opening a local file; if so, run a local server from this folder (for example: `python -m http.server 8000`) and open http://localhost:8000 in Chrome.
