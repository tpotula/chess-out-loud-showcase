# Chess Out Loud
Chess analysis tool that reviews your moves alongside what you were thinking during the game to generate a comprehensive review that shows where you can improve

**Live site: https://chess-out-loud.fly.dev**

## How it works

1. A Chrome extension records your voice while you play on Chess.com/Lichess. 
2. When the game ends, your narration is transcribed and matched to the move
   you were thinking about.
3. The engine evaluates every position, and a deterministic layer works out
   what was actually true: threats, tactics, missed ideas.
4. A language model then compares your stated reasoning to those facts and
   writes coaching feedback of both the moves you made and what you were thinking
5. Over many games, the app surfaces patterns in how you think and what you can improve on

## Tech stack
JavaScript, React, Vite, Python, FastAPI, REST API, Manifest V3, , Gemini and OpenAI APIs, PostgreSQL, Docker
