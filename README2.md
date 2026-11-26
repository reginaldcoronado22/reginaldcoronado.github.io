CORONA CUT // Interactive Video Editor Portfolio & 30-Second Clip Stitcher

CORONA CUT is an interactive, browser-based Non-Linear Editing (NLE) showcase built for Reginald Coronado’s video editing portfolio (reginaldcoronado.github.io). Rather than passively watching a static showreel, recruiters, clients, and fellow editors can actively test pacing, color grading, transitions, and title overlays directly in their browser—and render a custom 30-second video reel without installing any software.

Why This Project Is Useful

Hands-On Portfolio Experience: Demonstrates core post-production workflows (trimming, rhythm, transitions, LUT color grading, and broadcast safe margins) in a live interactive sandbox.

100% Client-Side & Privacy-First: All video compositing, frame rendering, and .webm encoding run locally inside the user's browser via the HTML5 <canvas> and MediaRecorder APIs. Local video uploads are never sent to an external server.

Zero Copyright Friction: Ships with four procedurally generated 16:9 motion B-roll clips rendered via mathematical canvas code, requiring zero external stock media or licensed audio files.

Single-File Portability: Engineered as a self-contained index.html application that deploys effortlessly to static hosts like GitHub Pages.

What You Can Do With This Project

Stitch & Trim a 30-Second Showreel: Combine pre-loaded procedural B-roll clips (01_Cyber_Grid_Intro, 02_Kinetic_Wave_BRoll, 03_Neon_Pulse_Action, 04_Minimal_Outro_Card) or import your own local .mp4 / .webm clips, trimming each segment between 2.0s and 15.0s to hit the 00:30.0 target.

Apply Live Color Grading (LUTs): Toggle in real time between Rec.709 Clean, Teal & Orange Cinematic, Moody Noir, and Vintage 16mm Film.

Customize Incoming Transitions: Test Hard Cut, Cross Dissolve, Dip to Black, and Whip Slide transitions between timeline clips.

Edit Lower-Thirds & Kinetic Titles: Customize main title text, role tags, and overlay layouts (Broadcast Lower-Third, Cinematic Center Title, or Director Viewfinder HUD), plus toggle broadcast safe-margin guides.

Render & Export Master Video: Composite the active timeline, color grade, and graphics into a downloadable .webm video file directly from the browser.

How to Use It

Option 1: Use the Live Web App

Visit https://reginaldcoronado.github.io:

Press PLAY REEL (or hit Spacebar) to preview the default 30-second sequence.

Click any clip block on the Sequence Timeline to adjust its trimmed duration, incoming transition, or track order in the Clip & Cut Inspector.

Open the Media Bin to add additional B-roll or click + Upload Clip (MP4/WebM) to test your own footage locally.

Click Render & Export Reel in the top-right header to encode and download your stitched .webm file.

Option 2: Run or Customize Locally

Clone this repository:

git clone https://github.com/reginaldcoronado/reginaldcoronado.github.io.git
cd reginaldcoronado.github.io


Open index.html directly in any modern desktop or mobile browser (Chrome, Edge, Firefox, or Safari)—no build step, Node.js server, or package installation required.

Community, Contributions & Governance

Contributing: Want to add a new procedural B-roll generator, transition shader, or LUT preset? Read CONTRIBUTING.md before submitting a pull request.

Code of Conduct: Please review our CODE_OF_CONDUCT.md to help keep this project welcoming and constructive.

Citation: If you reference or adapt this interactive NLE engine in your own portfolio or research, see CITATION.cff.

License: Distributed under the MIT License. See LICENSE for details.
