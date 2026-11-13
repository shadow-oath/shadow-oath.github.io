SHADOW OATH - PUT IT ONLINE + INSTALL ON IPHONE (free)

A) Put the game online at https://shadow-oath.github.io (one time)
 1. Sign in at https://github.com
 2. Click "+" (top right) > New organization > Free plan.
    Organization name: shadow-oath   (this is what makes the link say "shadow-oath")
 3. Inside the new organization, click New repository.
    Repository name: shadow-oath.github.io   (exactly this) · Public · Create.
 4. Click "uploading an existing file" and drag in ALL 7 files from this folder:
      index.html  manifest.webmanifest  sw.js  icon-192.png  icon-512.png  apple-touch-icon.png  README.txt
    Click "Commit changes".
 5. Settings > Pages > Branch: "main", folder "/ (root)" > Save.
 6. Wait 1-2 minutes. Your game is at:  https://shadow-oath.github.io
 7. Firebase console > Authentication > Settings > Authorized domains:
    make sure  shadow-oath.github.io  is in the list.

B) Install it on the iPhone
 1. Open https://shadow-oath.github.io in SAFARI.
 2. Share button > "Add to Home Screen" > Add.

C) Online play
 - On the title screen tap "Log in / Create account". Username + password only, no email.
   The same username and password work on any phone or PC, and your 3 save slots follow you.
 - There is no password reset, so remember your password.
 - Players in the same chapter share one world: same monsters, co-op bosses (boss gets
   +70% HP per extra player in the arena), emotes, and opt-in duels (tap a player).
 - Menu > Online: who's online, join a friend's chapter, turn online play on/off.
 - Menu > Leaderboard: players and faction ranking.

Updating later: upload the new index.html (replace) and change VERSION in sw.js
(e.g. shadow-oath-v5). The app updates the next time it's opened with internet.
