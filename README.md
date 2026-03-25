# 🎬 MOVIKO — Movie Solution

MOVIKO is a lightweight movie-first streaming interface built for a simple, premium experience in Hebrew.

It is designed to feel clean and direct:
- open the app
- search a movie
- choose the best source automatically
- watch with Hebrew subtitles when available

The project uses preconfigured add-on endpoints and a minimal UI so the user does not need to manage technical settings manually.

---

## Main goals

- Hebrew-first interface
- very simple user flow
- automatic catalog refresh on app startup
- automatic subtitle preference for Hebrew
- default playback preference for 1080P
- optional 4K switch only when available
- built-in splash video and buffering animation
- premium branded MOVIKO experience

---

## Current features

### Interface
- RTL Hebrew layout
- branded MOVIKO top bar
- search bar for movies
- SIGN IN and SIGN UP buttons
- movie catalog grid
- featured movie panel
- IMDb badge
- Trailer button
- Add to Library button

### Startup experience
- splash screen with intro video
- optional click-to-unmute behavior depending on browser autoplay rules

### Buffering experience
- custom looping buffering video
- circular masked loader while the movie is loading in the background

### Source selection
- default preference: **1080P with the highest user count**
- optional secondary choice: **4K with the highest user count**
- avoids showing too many confusing options in the UI

### Subtitle behavior
- tries to fetch Hebrew subtitles automatically
- prefers one matching Hebrew subtitle when available

---

## Configured add-ons

The interface is configured to work with these endpoints:

- Cinemeta  
- OpenSubtitles v3  
- OpenSubtitles legacy  
- Wizdom  
- Torrentio  

> Important: some browsers restrict live requests when opening the app with `file:///...`.  
> For real testing, run the project through a local server.

---

## Project structure

```text
MOVIKO/
│
├── index.html
├── README.md
├── buffering.mp4
├── splash.mp4
├── MOVIE SOLUTION.mp4
├── logopop.png
├── logopop_tlv.png
└── placeholder_light_gray_block.png
```

---

## Run locally

Open PowerShell in the project folder and run:

```powershell
cd "C:\Users\SUNRIDE\IPTV INTERFACE"; python -m http.server 5500
```

If `python` is not recognized, use:

```powershell
cd "C:\Users\SUNRIDE\IPTV INTERFACE"; py -m http.server 5500
```

Then open:

```text
http://localhost:5500/index.html
```

---

## Why run through a local server

If you open the app directly with `file:///C:/.../index.html`, some add-on requests may fail because of browser security restrictions.

Running through a local server helps:
- addon fetch requests work more reliably
- poster images load more consistently
- video and asset paths are easier to debug
- the app behaves closer to production

---

## Known limitations

- This is currently a front-end prototype / interface layer.
- Final real playback depends on external add-on responses.
- Browser autoplay policies may mute or block video sound until user interaction.
- Some add-on endpoints may change or become unavailable over time.
- Source ranking is currently simplified to keep the UI minimal.

---

## Planned improvements

- real account system with email verification
- persistent watch history
- continue watching
- better live source parsing
- better trailer integration
- richer movie details page
- player quality switch inside the video player
- automatic live subtitle injection flow
- packaged desktop app version with Electron
- auto-update system for users

---

## Disclaimer

MOVIKO is an interface layer and discovery shell.

It does not claim ownership over third-party metadata, subtitle services, or streaming sources. Availability, legality, quality, and reliability of external content depend on the connected third-party add-ons and services.

Use and distribution should comply with the laws, licenses, and terms that apply in the relevant jurisdiction.

---

## Branding

Project name: **MOVIKO**  
Tagline: **Movie Solution**

---

## Author

Created for **SUNRIDE**
