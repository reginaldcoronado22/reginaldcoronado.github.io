Contributing to CORONA CUT

Thank you for your interest in contributing to CORONA CUT (reginaldcoronado.github.io)! Whether you are fixing a browser rendering quirk, proposing a new procedural B-roll animation, or adding a color LUT preset, your help is welcome.

Please read through these guidelines to ensure a smooth review process. All participants are expected to abide by our Code of Conduct.

How Can I Contribute?

1. Reporting Bugs

If you encounter an issue with timeline scrubbing, transition rendering, or .webm export across specific browsers:

Check existing GitHub Issues first to avoid duplicates.

Open a new issue clearly describing:

Your browser and operating system (e.g., Chrome 130 on Windows 11, Safari on macOS).

Steps to reproduce the behavior.

Expected result vs. actual result (screenshots or console logs are very helpful).

2. Suggesting Enhancements

Have an idea for a new feature—such as audio waveform visualization, keyboard J-K-L shuttle controls, or additional transition styles?

Open an issue labeled enhancement explaining how the feature improves the interactive editing showcase while keeping the app lightweight and dependency-free.

3. Submitting Pull Requests

Fork & Branch: Fork the repository and create a descriptive branch from main (e.g., feat/new-lut-preset or fix/mobile-scrubbing).

Preserve Single-File Simplicity: Keep all HTML, Tailwind utility classes, custom CSS, and vanilla JavaScript self-contained within index.html unless discussed beforehand in an issue.

Copyright & Asset Rules:

Do not commit copyrighted video, audio, or font files to the repository.

Any new built-in clips must be procedurally generated using the HTML5 Canvas 2D API.

Test Locally: Verify that playback (Spacebar), timeline scrubbing, clip trimming, LUT switching, and .webm export work cleanly without console errors on both desktop and mobile viewports.

Open a Pull Request: Provide a clear summary of your changes and link any related issues.
