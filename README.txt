# 60 DAYS — Board Mission (Offline PWA)

## What's included
- Five daily subjects: Maths, Physics, Chemistry, Hindi and English
- 60-day date calendar starting 25 November 2026
- Each day shows the subject chapter and its Day X / Y
- Daily checkboxes, personal targets, automatic next-day and 7-day revision checklist, chapter editor, backup and restore
- Offline cache using a service worker

## Important: install once while internet is available
A PWA must be opened from a secure website (HTTPS) or localhost. Opening `index.html` directly from a file manager may let the page run, but it cannot install the offline service worker.

### Easiest free hosting: GitHub Pages
1. On a device with internet, sign in to GitHub and create a new **public** repository, e.g. `board-mission`.
2. Upload **all contents of this folder** (index.html, manifest.webmanifest, sw.js, icons folder) to the repository root.
3. In repository Settings → Pages, choose **Deploy from a branch**, branch `main`, folder `/root`, then Save.
4. Open the published HTTPS address in Chrome on your Android tablet/phone.
5. Wait for the page to finish loading once. Chrome menu (⋮) → **Install app** or **Add to Home screen**.
6. Open the installed app once while online. Then switch off internet and test it.
7. Keep the browser/app data. Use **Backup** regularly.

## Schedule note
The app distributes each subject's chapter list across 60 days, so all five subjects appear every day. Chapter duration weights can be edited in Subjects & Chapters; choose **Rebuild plan** to recalculate. These are editable planning allocations, not official BSEB weightage or a guarantee of chapter workload.
The chapter lists are transcribed from the user's photographed book contents. Please cross-check spelling and the current exam syllabus against school/board guidance.
