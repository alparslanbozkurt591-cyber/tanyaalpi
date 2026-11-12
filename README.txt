TanyaAlpi - your spending tracker
=================================

This folder is the whole app. It does not need Claude or a subscription.
Your data is saved inside the web browser you use it in, on that device only.


WHAT'S IN THE FOLDER
--------------------
  index.html              The app
  Open TanyaAlpi.bat      Double-click to open the app on Windows
  Open TanyaAlpi.command  Double-click to open the app on a Mac
  lib\                    Excel export and PDF reading tools (so they work offline)
  icons\                  App icons with the Ukrainian and Turkish flags
  manifest.webmanifest    Lets phones install it like an app
  sw.js                   Lets it work offline once installed from a web address
  README.txt              This guide

Keep all the files together in one folder.


1. USE IT ON YOUR COMPUTER
--------------------------
  1. Unzip the folder somewhere you'll keep it, such as Documents.
     (Don't run it from inside the zip.)
  2. Double-click "Open TanyaAlpi.bat" (Windows) or "Open TanyaAlpi.command" (Mac).
     You can also just double-click index.html.
  3. It opens in your browser. Chrome or Edge work best.

  Always open it the same way, from the same place, in the same browser.
  If you move the folder or switch browser, it starts empty
  (restore a backup to get your data back, see section 4).


2. PUT IT ON YOUR IPHONE (as an app with its own icon)
------------------------------------------------------
  An iPhone can't run apps from a downloaded folder, so put the folder on a
  free website first. Only the app goes online. Your spending data never
  leaves your phone.

  Easiest way, with Netlify (free):
  1. On your computer, go to https://app.netlify.com/drop
  2. Sign up for a free account so the site stays online.
  3. Drag the whole TanyaAlpi folder onto the page.
  4. Netlify gives you a web address, like https://something.netlify.app
     (you can rename it in the site settings).
  5. On your iPhone, open that address in Safari.
  6. Tap Share, then "Add to Home Screen", then Add.

  TanyaAlpi now has its own icon with both flags, opens full screen,
  and works offline after the first time you open it.

  Other free hosts work the same way, for example GitHub Pages or Cloudflare Pages.


3. MOVE YOUR DATA FROM THE CLAUDE VERSION
-----------------------------------------
  1. Open TanyaAlpi on claude.ai, go to Settings (the gear icon), and tap "Copy backup".
  2. Open this version, go to Settings, then "Restore from a backup".
  3. Paste the text and tap "Replace everything with this backup".

  You can also save the backup text as a .txt or .json file and use
  "Or choose a backup file".


4. KEEP YOUR DATA SAFE
----------------------
  This version saves data in the browser on each device. It does NOT sync
  between your phone and computer, and clearing your browser's history and
  website data deletes it.

  So back up regularly:
  - Settings > Copy backup, and paste it into a note or file you keep.
  - Settings > Export to Excel, for a tidy copy you can read anywhere.

  To move data between devices, copy a backup on one and restore it on the other.


5. GOOD TO KNOW
---------------
  - Fonts load from the internet the first time. Offline, it uses your
    phone's or computer's own fonts and looks almost the same.
  - Importing statements, Excel export, insights and the spending score
    all work offline.
