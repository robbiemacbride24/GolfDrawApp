Lovey Golf Section — Outing Draw

A single-file web app for running a randomised golf group draw at section outings. Built for Lovey Golf Section (est. 2014) — add your players once, mark who's playing each outing, and let the app sort everyone into fair groups with an animated reveal.

No backend, no build step, no install — it's one HTML file that runs entirely in the browser.

Features


Saved player roster — add everyone in the section once. Names, handicaps, and buggy requirements are saved on your device so you never have to re-enter them.
Mark who's in or out — before each outing, tick off who isn't coming. Only players marked "In" go into the draw.
Handicaps — stored per player and editable in-app at any time (tap the handicap badge to update it), since they change throughout the season.
Buggy pairing — players who need a buggy are automatically paired up two-to-a-buggy, and the draw avoids putting two buggy pairs in the same group unless there genuinely aren't enough groups to go around.
Flexible group sizes — choose Automatic (best mix of 3s and 4s), Prefer 3-balls, or Prefer 4-balls.
Animated draw reveal — a full-screen sequence (shuffle → group-by-group reveal → final results with confetti) for showing the draw on a big screen at the clubhouse.
Light/dark mode toggle.
Works on iPhone — installs to your Home Screen as a standalone app via Safari's "Add to Home Screen."


Usage


Open Lovely_Golf_Draw.html in a browser (see Installing on iPhone below for mobile).
Step 1 — Add players to your roster. Add players one at a time (with name, handicap, and buggy requirement), or paste a list in the format Name, Handicap (one per line). This only needs doing once — the roster is saved automatically.
Step 2 — Mark who's playing. Everyone defaults to "In." Tap a name to toggle them "Out" if they're not at this outing. You can also toggle buggy requirements here, or tap a player's handicap to edit it.
Step 3 — Review the field. Confirms who's actually in today's draw.
Step 4 — Choose a group format. Automatic, Prefer 3-balls, or Prefer 4-balls.
Step 5 — Start Draw. Runs the full-screen animated reveal and shows the final groups.


Use Reset outing to clear today's In/Out selections without touching your saved roster, or Clear saved roster to wipe everyone permanently.

Installing on iPhone


Get the HTML file onto your phone (AirDrop, email it to yourself, or save it via the Files app/iCloud Drive).
Open it in Safari (not a Mail preview or other app).
Tap the Share icon → Add to Home Screen → Add.


You'll get an app icon that opens full-screen, with your roster and handicaps saved locally on that device between visits.

Data storage

Your roster is saved using the browser's local storage — there's no server and no account. This means:


Data is private to the device and browser you used to add it.
It persists across visits as long as you don't clear Safari's site data or remove the Home Screen icon.
It does not sync between devices. If you use the app on a second phone or tablet, you'll need to build the roster there too.


Tech

Plain HTML, CSS, and vanilla JavaScript in a single file — no frameworks, no dependencies, no build process. Just open it in a browser.

License

Built for personal/section use. Feel free to fork and adapt for your own golf section's outings.
