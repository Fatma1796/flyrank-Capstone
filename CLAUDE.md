CLAUDE.md
Context for any AI coding assistant (Claude Code, Cursor, Gemini CLI, Copilot, etc.) working in this repo. Keep this updated as real decisions get made — vague rules aren't useful to the assistant or to you.
Project
OpsPilot — an internal AI-assisted tool for a real small-business operator (placeholder problem: client intake + daily-ops summaries; replace once the specific operator/workflow is confirmed). This is the FlyRank Frontend AI Engineering track capstone repo — it will grow week over week through the whole 8-week track, not get replaced.
Stack (planned — update once FE-04/FE-05 scaffold the app)
Next.js (App Router), TypeScript
Tailwind CSS for styling
Server Components by default; Client Components only where interactivity is required
Deployment: Vercel
AI: Claude API (or another LLM) — used for structured output, not just a chat box
Conventions
Commits follow Conventional Commits (feat:, fix:, chore:, docs:, test:, ...)
One feature branch per assignment/drill; don't rewrite history on main
Forms use validated, controlled inputs (library TBD once scaffolded — document the choice here once picked)
No secrets committed — use .env.local, keep it gitignored
Every screen must be responsive at 375px and 1280px
Notes for the assistant
This repo is Week 1 of an 8-week track. Don't assume production app code exists yet — FE-01 is repo/tooling setup only.
When asked to critique the README, focus on clarity for a reviewer who has never seen this project before, not on adding unnecessary sections.

