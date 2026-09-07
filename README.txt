JOB HUNT - publish package
==========================

Upload EVERYTHING in this folder to any static web host. index.html is the whole
game (sprites, music, and sounds are embedded); the other files are the icons
and the web-app manifest for "Add to Home Screen" on iPhone/Android.

GitHub Pages
   New public repo (e.g. job-hunt) -> "Add file" -> "Upload files" -> drop these
   files -> Commit. Then Settings -> Pages -> Source: "Deploy from a branch",
   Branch: main / (root) -> Save. Live in ~1 minute at
   https://YOUR-USERNAME.github.io/job-hunt/

Notes
- Sound starts on the first tap (browser autoplay rules). On iPhone the ring/
  silent switch also silences the game.
- Share the same URL for desktop and phones; on desktop the game is centred at
  phone width and uses the keyboard (arrows, O, L, M).
- To update the game later, replace index.html and re-upload.
