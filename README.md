Part 1: Install (one time)
Unzip on your phone. In the Files app, long-press Rupee_App.zip → Extract. You get a rupee folder with 7 files.
Make a free GitHub account at github.com if you don't have one. Create a new repository named rupee and set it to Public. Only the app code goes there, never your data.
Upload the files. In the repo tap Add file → Upload files, select all 7 files from the folder, then Commit changes.
Turn on hosting. Go to Settings → Pages, set Source to Deploy from a branch, pick main and / (root), then Save.
Wait about 1 minute. Your link will be https://YOURNAME.github.io/rupee/.
Open that link in Chrome. Tap ⋮ → Add to Home screen (or Install app). Open Rupee from the new icon.
No-account alternative: in Termux run cd rupee && python -m http.server 8080, open localhost:8080 in Chrome, and use Add to Home screen. After the first install it works offline without Termux, but GitHub Pages is the more reliable option.
Part 2: First use
Open More and enter your monthly income, then tap Save income.
In More, tap Import CSV and pick your Kotak statement.
On the review screen, set a category for each merchant marked New (the person names). The app remembers each choice.
Tap Import. You land on that month's Overview.
Open Plan to set limits, for example Food ₹3,000.
For daily use, tap the brass +. Type the amount and a note like "lunch" and the category fills in.
Part 3: Every month
Download the new statement from Kotak.
Import it. Old entries are skipped automatically.
Use the ‹ › arrows to look at past months.
Tap Backup everything in More and keep the file in Google Drive.
Common problems
No "Install" option: make sure you opened the https link in Chrome, not inside another app.
Updating the app later: upload the new index.html to GitHub, then close and reopen Rupee twice.
Wrong category on a transaction: tap it, change it, and keep "apply to all" ticked.
Tell me which step you're on if anything doesn't match what you see.
