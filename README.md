# Quest Map — legal pages

Public privacy policy for **Quest Map** (C85 Games), hosted on GitHub Pages. Google Play blocks
the first release until a privacy policy URL is set, because the app uses location and camera.

Static HTML and CSS only: no JavaScript, cookies, analytics or third-party requests.

## Publish (about five minutes, free)

1. On github.com (account `brianwands656-c85`), create a new **PUBLIC** repository named
   `quest-map-legal`. Leave **Add README**, **.gitignore** and **licence** all **off**. This
   folder already has a commit, and a README created on GitHub would make the push fail.
2. From this folder:

       git remote add origin https://github.com/brianwands656-c85/quest-map-legal.git
       git push -u origin main

3. Repo **Settings > Pages**: Source **Deploy from a branch**, branch **main**, folder **/ (root)**, Save.
4. After a few minutes this opens:
   **https://brianwands656-c85.github.io/quest-map-legal/privacy-policy.html**
   Paste that into Play Console > App content > Privacy policy.

The page must stay reachable for the app's whole life: never rename, delete or make this repo
private (private silently switches Pages off on the free plan).

If the app starts handling data differently, update the policy **before** that version ships.
