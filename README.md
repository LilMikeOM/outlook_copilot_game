# Inbox Action Wheel

A Wheel of Fortune–style game for the Wells Fargo "From inbox overload to action" Copilot in Outlook training. Spin for points, guess consonants, buy vowels, solve phrases pulled from the training deck. Supports 2–4 teams.

## Play it

Open `index.html` in any browser — no install, no internet needed after load (fonts fall back gracefully).

## Put it on GitHub + get a shareable link (GitHub Pages)

1. Go to **github.com** → sign in → click **+** (top right) → **New repository**
2. Name it something like `inbox-action-wheel`, keep it **Public**, click **Create repository**
3. On the new repo page, click **uploading an existing file**
4. Drag in `index.html` and `README.md` → click **Commit changes**
5. Go to **Settings** → **Pages** (left sidebar)
6. Under "Branch", pick **main** and **/ (root)** → **Save**
7. Wait ~1 minute, refresh — your link appears at the top:
   `https://YOUR-USERNAME.github.io/inbox-action-wheel/`

Open that link on the presentation machine and you're live.

## Host cheat sheet

- **Spin** → tap a consonant → correct letters pay spin value × count, and you keep the turn
- **Vowels** (gold keys) cost 250, no spin needed
- **Solve** → +500 bonus; wrong guess passes the turn
- **Bankrupt** wipes that team's points for the current round only
- **Host: reveal all** ends a round if time runs short
- Physical keyboard letter keys work as a shortcut

## Answer key

| # | Category | Phrase |
|---|----------|--------|
| 1 | Copilot Tip | LET COPILOT SUMMARIZE LONG THREADS |
| 2 | Copilot Tip | ASK COPILOT TO CATCH YOU UP |
| 3 | Copilot Tip | COACH YOUR DRAFT BEFORE YOU SEND |
| 4 | Copilot Tip | TEACH COPILOT WHAT MATTERS MOST |
| 5 | Outlook Tip | TRIAGE YOUR INBOX IN PLAIN ENGLISH |
| 6 | Outlook Tip | TURN ONE INSTRUCTION INTO A RULE |
| 7 | Prompt Tip | PROMPT WITH GOAL CONTEXT AND OUTPUT |
| 8 | Meeting Tip | SCHEDULE MEETINGS RIGHT FROM THE THREAD |
| 9 | Planning Tip | PLAN YOUR WHOLE DAY WITH ONE PROMPT |
| 10 | Habit Tip | START WITH ONE WORKFLOW AND REPEAT THE WIN |

To change puzzles, edit the `PUZZLES` array near the top of the `<script>` in `index.html` (letters and spaces only — keep phrases in CAPS).
