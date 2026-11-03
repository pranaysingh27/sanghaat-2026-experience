SANGHAAT 2026 — THE HEIST WEBPAGE

FILES
- index.html: webpage, opening screen, music controls, page navigation and registration hotspots
- assets/bella-ciao.mp3: supplied audio file (verified as MP3 audio)
- assets/pages/page-01.jpg ... page-23.jpg: optimized page images from your supplied PDF

PUBLISH TO GITHUB PAGES (phone or computer)
1. Download and unzip sanghaat-2026-webpage.zip.
2. Create a NEW repository on GitHub, for example: sanghaat-2026-experience
3. Upload the contents INSIDE this folder (index.html and the assets folder) to the repository root. Do not upload the outer folder itself as a nested folder.
4. In the repository, open Settings > Pages.
5. Under Build and deployment, choose Deploy from a branch; select main and /(root), then Save.
6. Wait a minute or two and open the Pages URL shown in Settings > Pages.

IMPORTANT
- The audio starts only after the visitor taps PLAY THE HEIST, because mobile browsers require a user gesture.
- This version displays all 23 pages as optimized images for smooth vertical scrolling.
- Registration hotspots are overlaid on the pages based on the supplied PDF's embedded links. Test each link after publishing, especially page 10, which has two embedded link annotations.
- The uploaded audio was detected as MP3 despite its original filename; it has been copied to assets/bella-ciao.mp3 without changing the audio data.
- If a Google Form URL is not the correct event form, update the URL in the pageLinks object in index.html.
