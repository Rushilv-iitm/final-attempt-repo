# Overview
Final Test Website is a standalone, offline web app to build, take, and grade tests. It supports multiple choice, true/false, and short answer questions, a countdown timer with optional auto-submit, shuffling, pass marks, explanations, progress tracking, export/import as JSON, and a print-friendly results view for certificates. Everything is saved in your browser (localStorage) — no server required.

# Setup
- No installation needed. Open index.html in any modern browser.
- All assets are embedded; works fully offline.
- Optional: Use a local HTTP server for best file access behavior, though not required.

# Usage
1. Taking the Sample Test
   - Open the page and click Start Test.
   - Answer questions; your progress auto-saves if you click Save.
   - Submit anytime, or wait for auto-submit when the timer ends (if enabled).
   - Review detailed feedback with correct answers and explanations.
   - Click Print Certificate to print or save as PDF.

2. Building Your Own Test
   - Go to the Build tab.
   - Edit Title, Description, Time Limit, Pass Mark, Shuffle, and Auto-submit options.
   - Add questions (Multiple Choice, True/False, Short Answer).
   - For MC, mark the correct option using the radio button beside it.
   - For Short answers, add one or more acceptable answers (case-insensitive).
   - Reorder with Move Up/Down; Delete as needed.
   - Click Save Test to persist changes locally.

3. Import/Export
   - Export: Click Export JSON in Take or Build to download the current test.
   - Import: Click Import JSON and select a .json file matching the test format.

4. Shortcuts
   - ? — Show shortcuts
   - S — Submit test (Take view)
   - Ctrl/Cmd + S — Save progress
   - J / K — Next / Previous question
   - G — Scroll to top

5. Tips
   - Progress badges in navigation turn green when a question is answered.
   - Short answers use exact, case-insensitive matching.
   - Use the Settings tab to toggle light theme and manage local storage.
   - Use Print to generate a paper/PDF copy of results.

# If Round 2
N/A (Round 1 build).