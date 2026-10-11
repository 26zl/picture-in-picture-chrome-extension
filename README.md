# Picture-in-Picture Chrome Extension

> **Fork notes.** This fork changes two things in `src/script.js` so the shortcut also works on sites such as
> Disney+: videos inside open shadow roots are found, and a player's `disablePictureInPicture` hint is cleared
> when the user explicitly triggers the extension. Everything else is upstream. Install it unpacked from
> `chrome://extensions` (Developer mode → Load unpacked → the `src` folder) and give it the Alt+P shortcut.

A simple Chrome Extension to demonstrate the [Picture-in-Picture Web API](https://wicg.github.io/picture-in-picture/) in Chrome.

Get it on the Chrome Web Store at https://chrome.google.com/webstore/detail/hkgfoiooedgoejojocmhlaklaeopbecg

<img src="https://raw.githubusercontent.com/beaufortfrancois/picture-in-picture-chrome-extension/master/screenshot.png">

## Configuration

The keyboard shortcut (defaults to `Alt-P`) can be changed on the
Chrome Extension Shortcuts settings page:
chrome://extensions/shortcuts
