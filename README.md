# NEXORA — Your learning. Your progress. Your future.
Stage 1: Dashboard, My Learning Studio (Topic Tracker + AI Assistant demo), Focus Timer. Runs in local demo mode (browser storage); no keys needed.
## Run
    npm install
    npm run dev
## Build
    npm run build   # output in dist/
## Deploy (Vercel)
Push to GitHub, import the repo at vercel.com. Build: `npm run build`, output: `dist` (set in vercel.json).
## GitHub
    git init && git add . && git commit -m "NEXORA stage 1"
    git branch -M main && git remote add origin <YOUR_REPO_URL> && git push -u origin main
## Not yet built
Notes, Flashcards, Revision Planner, Study Techniques, Exams, Attendance, Assignments, Timetable, Analytics, Leaderboard, Profile, real AI backend, Supabase wiring (schema is in supabase/migrations).
The AI Assistant is a clearly labelled demo; YouTube links are search links only.
