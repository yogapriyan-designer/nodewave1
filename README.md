# Attendance Intelligence

Single-file web app (no build step, no API keys, free).

## Run in VS Code
1. Open this folder in VS Code (File > Open Folder).
2. Install the "Live Server" extension, right-click index.html > "Open with Live Server".
   (Or simply double-click index.html to open it in a browser.)

## Where to edit
All inside index.html:
- Timetables:  const T = {...}   (DATA LAYER section)  + const N = {...} for subject names
- Thresholds:  const CFG = {min:75, target:90}
- Calculation formulas: CALCULATION ENGINE section
- Chatbot logic: function advise(...)  (rule-based, runs locally, free)

Data is saved in the browser (localStorage).
