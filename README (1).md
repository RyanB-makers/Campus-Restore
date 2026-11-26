# Campus Restore: a Network+ study game

A free, single-page study game for the CompTIA Network+ **N10-009** exam.

- Study short lesson cards for each of the 25 exam objectives.
- Each objective is a network link on a campus map. Pass a 5-ticket shift (4 of 5 right) to bring the link back up.
- Links flicker when a review is due (after 2, 4, 7, 14 and 30 days), so you keep material fresh.
- Clear all the links in a building to unlock its timed "outage night" (15 tickets, target 80%).
- The final boss is a timed 90-question, 90-minute practice exam scored by domain (target 85%).
- Six mini games in the **Campus Arcade** (tap Arcade on the map): Port Rush (1.4), Subnet Sprint (1.7), Layer Drop (1.1), Cable Closet (1.5), Fix It In Order (5.1) and Attack ID (4.2). Each round is 60 to 90 seconds, earns XP and bronze, silver or gold medals, and missed answers come back more often.
- A 16-week plan sets which objectives to study each week. You choose the start date.
- **Stats** (tap Open stats under this week's card): an exam readiness gauge weighted by the N10-009 domain weights, your recent scores against the 85% target, a radar of your first pre-test against now, a 25-objective mastery map and your arcade high scores.
- **Lesson videos**: every objective has a narrated diagram video, under 2 minutes, with captions burned in. Tap **Watch the video** on the first lesson card, or **Video** on any later card. Watching most of a video marks it watched and earns 10 XP.
- A 25-question **pre-test**, one ticket per objective, sets your baseline. Retake it every 4 weeks to see how far you've come.

Every lesson and question was written fresh and fact-checked twice against CompTIA's N10-009 objectives, RFCs and vendor documentation.

## Saving progress

Progress, including your score history, is saved in your own browser (localStorage). Nothing is sent anywhere. To move it to another device, use **Download progress** and then **Load progress file** on the other device. Clearing your browser data erases it, so download a copy now and then.

## Running it

It is `index.html` plus a `videos` folder of 25 MP4 files, named by objective (`1.1.mp4` to `5.5.mp4`). Keep the folder next to `index.html`. Open the page in any modern browser, or host both on any static web host (GitHub Pages, Netlify and others). Without the `videos` folder, everything else still works and the video panel says the file is missing. The fonts load from Google Fonts. Without a connection, the page falls back to system fonts and still works.

### Uploading to GitHub Pages

1. In the repository, choose **Add file**, then **Upload files**.
2. Drag in `index.html`, `README.md` and the whole `videos` folder, then commit.
3. Wait a minute or two for Pages to rebuild, then reload the site.

The videos total about 65 MB, and each one is well under the 25 MB limit for files added in the browser. If the browser upload balks at that many files at once, upload the `videos` folder in two batches.

## Disclaimer

Not affiliated with or endorsed by CompTIA. CompTIA and Network+ are trademarks of CompTIA, Inc. Use this alongside official study materials.
