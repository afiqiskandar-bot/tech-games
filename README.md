# THE EXIT — YEAR ONE

## Upload to GitHub Pages

1. Go to https://github.com and sign in.
2. Click **New repository**.
3. Name it `the-exit-year-one`.
4. Create the repository.
5. Upload these three files to the repository root:
   - `index.html`
   - `style.css`
   - `script.js`
6. Commit the files.
7. Open **Settings → Pages**.
8. Under **Build and deployment**, choose **Deploy from a branch**.
9. Select branch **main** and folder **/(root)**.
10. Click **Save**.
11. Wait 1–3 minutes and open the GitHub Pages URL shown there.
12. Test the URL on a phone.

## QR code

Once the page works, copy the GitHub Pages URL into a QR-code generator. Print:

SCAN TO PLAY
THE EXIT — YEAR ONE
15 MINUTES • ONE PHONE • ONE CHANCE

## Important for 50+ players

This version is fully playable, but the leaderboard uses browser `localStorage`, so each phone has its own leaderboard.

For the actual event, use a shared backend such as Supabase/Firebase:

phone → GitHub Pages → JavaScript → shared database → live leaderboard

Never put a Supabase service-role/secret key in browser JavaScript. Use only a browser-safe publishable/anon key with appropriate Row Level Security.

## Customise

Edit the `P` array in `script.js` to replace the puzzles with AEON360 first-year facts, milestones, campaign clues or team references.
