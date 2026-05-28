# Balloon Popping Game 🎈

## Launching the Balloon Pop Game — Step by Step

## Prerequisites (one time)

1. A modern browser (Chrome, Edge, or Firefox — Chrome/Edge recommended).
2. A working webcam, not in use by Zoom/Teams/Skype.
3. Python installed (almost certainly already there on your machine). Verify with python --version in a terminal.

## Start a local web server (required — won't work as a double-clicked file)

1. Open a terminal (Git Bash, PowerShell, or Command Prompt).
2. Change to the game folder:
cd /c/Users/gburke/Claude_projects/balloon-game
3. Start a local server on port 8000:
python -m http.server 8000
3. You'll see Serving HTTP on :: port 8000 .... Leave this terminal open while you play.

3. If python isn't found, try py -m http.server 8000 (Windows launcher) or use Node: npx http-server -p 8000.

## Open the game

4. In your browser, go to http://localhost:8000.
  - You should see the "🎈 Balloon Pop" title screen.
  - If you see a red file:// warning banner, you opened the file directly — go back to step 4 and use the http://localhost:8000 URL instead.
