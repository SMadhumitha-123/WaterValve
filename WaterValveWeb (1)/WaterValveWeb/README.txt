WATER VALVE - WEB APP (installable) + HOW TO GET AN APK

STEP 1 - PUT IT ON THE INTERNET (free, https needed for Bluetooth)
  Option A: Netlify Drop  -> go to app.netlify.com/drop, drag this whole folder in.
            You get a link like https://something.netlify.app
  Option B: GitHub Pages  -> new repo, upload these 5 files, Settings > Pages > Deploy from branch.

STEP 2 - INSTALL ON PHONE (this already behaves like an app)
  Open the link in Chrome on Android > menu (3 dots) > "Install app".
  Chrome builds a real WebAPK and puts it on your home screen.

STEP 3 - (OPTIONAL) DOWNLOAD A REAL .APK FILE
  Go to https://www.pwabuilder.com , paste your https link, press Start,
  then Package for stores > Android > Generate. Download the zip and
  take the .apk from it. Copy it to your phone and install.

Pico side: run the Bluetooth main.py (board name "WaterValve").
Commands: O = open, C = close, S = status.

LEAK ALERTS (v2)
  Tap "Turn on leak alerts" once on each device (PC and phone) and press Allow.
  When a leak is detected the app shows a notification, beeps and vibrates.
  Alerts only work while the app is open and connected to the board by Bluetooth.
  After uploading the new files to Netlify, close and reopen the app (or refresh)
  so the phone picks up the update.
