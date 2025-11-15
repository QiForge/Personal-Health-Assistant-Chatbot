# Personal Health Assistant Chatbot (Frontend Demo)

**Team:** Codecrafters  
**Team Leader:** Udit Sharma (2400351530032)

Personal Health Assistant Chatbot — a frontend-only demo that provides personalized diet suggestions, meal timings and sleep recommendations based on user-entered health profiles. All data (profiles & history) is stored locally in the browser using localStorage — no backend required for the demo.

## Features
- Save user profile (name, age, weight, height, goal)
- Generate rule-based recommendations: daily calories, sample meals, sleep/wake times, notes
- Chat-like interface to ask for recommendations
- Upload simple profile files (JSON / text) to prefill data
- History of previous recommendations stored in browser (localStorage)
- Quick demo-ready: open `index.html` to run

## How to run (Demo / Local)
### Option A — Open directly (no server)
1. Clone the repository:
   ```
   git clone <your-repo-url>
   ```
2. Open the project folder and double-click `index.html` (or drag it into your browser).

### Option B — Serve with a simple HTTP server (recommended)
Using Python:
```
python3 -m http.server 8000
# then open http://localhost:8000/index.html
```
Using VSCode Live Server:
- Install Live Server extension, open `index.html`, and click "Open with Live Server".

## Usage (demo script)
1. Fill the Profile form (left panel): name, age, weight (kg), height (cm), goal (maintain/lose/gain).
2. Click **Save Profile**.
3. Click **Get Recommendation** or ask in chat: _"What should I eat today?"_
4. View recommendation (calories, meals, sleep, notes).
5. Check **History** to view saved recommendations.

## Folder structure
- `index.html` — main demo page (chat UI + profile form)
- `styles.css` — styling
- `script.js` — client-side logic, recommendation engine, localStorage
- `README.md` — project description & instructions

## Deployment (GitHub Pages)
1. Push the repo to GitHub.
2. In repository Settings → Pages, select branch `main` and folder `/ (root)`.
3. Save — the site will be available at `https://<your-username>.github.io/<repo-name>/`

## Notes & Limitations
- Data stored only in browser localStorage — clearing browser data removes profiles & history.
- No authentication or server-side storage. For production, integrate a backend and DB.
- Recommendation engine is rule-based and simple — extendable.

## Team & Contributions
- Team: Codecrafters  
- Team Leader: Udit Sharma — 2400351530032 (Project lead, Backend & Integration lead, final demo assembly)
- Tarun Gautam — 2400351530031 (Frontend & UI)
- Vivek Prashad — 2400350100052 (Chatbot logic & suggestion engine)
- Vikhyat Shrivastava — 2400351530034 (Database/Integration, deployment, docs & testing)

## License
MIT