Credit to @aawezhussain

**YouTube Music Playlist Liker Script**
This JavaScript script automates liking songs in a YouTube Music playlist, specifically designed for the "Liked Songs" playlist, processing songs from oldest (bottom) to newest (top).

**Features:**
Automated Liking: Clicks "Like" buttons for unliked songs (aria-pressed='false') in a playlist.
Reverse Order Processing: Starts from the bottom (oldest songs) to align with YouTube Music's "Liked Songs" display order.
Auto-Scrolling: Scrolls to the bottom of the playlist to load all songs, handling lazy loading.
Random Delays: Waits 10–60 seconds between actions to mimic human behavior and avoid bot detection.
Progress Logging: Outputs detailed logs with elapsed time, songs liked, and songs remaining.
Skip Already Liked Songs: Detects and skips songs already liked, ensuring efficiency.

**Insturctions:**
Open the playlist you want to like in your browser (Chrome or another Chromium-based browser is recommended).
Press Ctrl + Shift + J to open the Developer Console.
If pasting isn’t enabled in the console, manually type allow pasting and press Enter to enable it.
Copy the text from youtube music auto playlist liker.js and paste it into the console, then press Enter.
