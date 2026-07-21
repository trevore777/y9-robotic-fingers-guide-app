# Robotic Fingers Learning Spaces Update

Added a new **Learning Spaces** tab with 10 guided spaces (2 per week for 5 weeks).

Features:
- Project tutorial/video links
- Teaching notes and check-understanding questions
- AI Coach prompt generator: Explain / Coach / Check Evidence
- Student evidence writing area
- AI/help declaration
- Image/screenshot upload stored in localStorage
- Own-words confirmation
- Save-to-My-Evidence state in localStorage
- Export all Learning Space evidence as JSON

Important: this is a static HTML app, so the AI Coach generates safe prompts for the school's approved AI tool. A true embedded AI chat requires a server/API endpoint and secure API key handling; do not place an API key in browser JavaScript.

Run:
npm install
npm run dev
Then open http://localhost:3000
