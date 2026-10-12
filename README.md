# NEO Player

**Minimal. Powerful. Yours.**

NEO Player is a browser-based media player built as a self-contained
HTML application. It focuses on a clean, modern interface, responsive
playback controls, customizable themes, and a liquid-glass-inspired
visual design.

## Features

-   **Single-file app** --- the interface, styling, and application code
    are packaged in one HTML file.
-   **Modern interface** --- dark surfaces, subtle borders, smooth
    transitions, and a cyan accent.
-   **Responsive layout** --- adapts the player controls and panels to
    different screen sizes.
-   **Media playback** --- open a local media file in the player.
-   **Playback controls** --- use the timeline, playback controls,
    volume, and playback-speed options where supported.
-   **Queue and track tools** --- includes player panels for media queue
    and track-related controls.
-   **Themes and appearance settings** --- customize the player's look
    using the built-in theme controls.
-   **Liquid-glass styling** --- translucent surfaces, blur effects, and
    layered shadows on supported browsers.
-   **Mini-player interface** --- a compact player layout for supported
    workflows.
-   **Keyboard help** --- a built-in help panel explains available
    shortcuts.
-   **Accessibility considerations** --- visible focus styles and
    support for reduced-motion and reduced-transparency preferences.

> **Compatibility note:** Media formats and advanced playback
> capabilities depend on the browser and the media file. Some embedded
> audio or subtitle tracks may not be available in every browser.

## Getting Started

### Option 1: Open the HTML file

1.  Download or clone this repository.
2.  Locate the main HTML file (`index.html`).
3.  Open it in a modern browser such as Chrome, Edge, or Firefox.
4.  Use the **Open/Browse** control to choose a media file from your
    device.

No build step or package installation is required for the self-contained
HTML version.

### Option 2: Run with a local server

If you prefer to serve the file locally, open a terminal in the project
directory and run:

``` bash
python -m http.server 8000
```

Then visit:

``` text
http://localhost:8000
```

## Usage

1.  Launch `index.html` in your browser.
2.  Select a local media file using the player's open/browse control.
3.  Use the playback controls and seek bar to control playback.
4.  Explore the built-in panels for themes, queue, tracks, sleep
    options, and keyboard help.
5.  Resize the browser window to see the responsive layout.

Available controls can vary depending on the media type and browser
support.

## Technology

-   HTML5
-   CSS3 (responsive layout, custom properties, transitions, and
    glass-style effects)
-   JavaScript
-   Native browser media capabilities

The current application is designed to run directly in the browser and
does not require a backend server for basic local playback.

## Browser Compatibility

Use a recent version of a modern browser for the best experience. Actual
playback support depends on the browser, operating system, codecs, and
media container. Features such as picture-in-picture, embedded tracks,
and fullscreen behavior may have browser-specific limitations.

## Project Structure

``` text
.
└── index.html    # Self-contained NEO Player application
```

If you rename the HTML file, update the filename in these instructions
accordingly.

## Known Limitations

-   Browser media engines do not support every video/audio codec or
    container.
-   Embedded subtitle and audio-track availability varies by browser and
    file.
-   Local files are played through browser APIs; this project is not a
    media transcoder.
-   Behavior may differ between desktop and mobile browsers.

## Contributing

Suggestions, bug reports, and improvements are welcome. When proposing
changes, please preserve the existing player features and test the
interface at both desktop and mobile sizes.

## License

No license has been specified yet. Unless a license is added to this
repository, all rights remain with the copyright holder and reuse is not
automatically permitted.

## Download

## Download NEO Player

Download the latest Windows installer from the [GitHub Releases page](https://github.com/alaqmarsaify/NEO-Player/releases/tag/v1.0.0).

1. Download `NEO-Player-Setup-1.0.0.exe`.
2. Open the downloaded file.
3. Follow the installation instructions.

**Note:** Windows may display a security warning because the installer is not code-signed.

------------------------------------------------------------------------

Made with care for a smoother, more personal media playback experience.

Main Player
<img width="1917" height="908" alt="Screenshot 2026-10-12 202040" src="https://github.com/user-attachments/assets/9dd6b7db-4c29-4a56-a600-b3a27a740eed" />

Light Theme
<img width="1917" height="911" alt="Screenshot 2026-10-12 202056" src="https://github.com/user-attachments/assets/8e3f0c99-7dc3-4549-9c69-a563e15df2eb" />

Extra Features
<img width="1868" height="837" alt="Screenshot 2026-10-12 202137" src="https://github.com/user-attachments/assets/3b047461-db9f-4c08-8d21-c5febb4f7c33" />
<img width="1092" height="842" alt="Screenshot 2026-10-12 202146" src="https://github.com/user-attachments/assets/e7055d34-13d0-431a-9c6f-578535d38985" />

