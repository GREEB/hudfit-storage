# HUD Fit storage bridge

A one-page helper for the HUD Fit Deadlock mod. The mod loads `index.html` in the game's hidden
browser and keeps HUD layouts in that browser's `localStorage`, on the player's own PC.

The page has no network access (its Content-Security-Policy is `default-src 'none'`), sends nothing
anywhere, and only answers the game through its page title.
