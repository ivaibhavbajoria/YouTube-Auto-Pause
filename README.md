# YouTube Auto Pause Chrome Extension

## Overview
"YouTube Auto Pause" is a Chrome extension that automatically pauses YouTube videos when you switch to another tab and resumes playing when you return. This extension helps save bandwidth and keeps you from missing any content while browsing other tabs.

## Features
- Automatically pauses YouTube videos when the tab is inactive.
- Resumes playing YouTube videos when the tab becomes active again.

## Installation

### Prerequisites
- Google Chrome browser

### Steps
1. Clone this repository or download the source code as a ZIP file and extract it.
2. Open the Chrome browser and navigate to `chrome://extensions/`.
3. Enable "Developer mode" by toggling the switch in the top-right corner.
4. Click on the "Load unpacked" button and select the directory where you cloned/extracted the extension files.
5. The extension will now be added to Chrome and will be active.

## Files and Directories
- `manifest.json`: Defines the extension's permissions, background script, content script, and the sites it will operate on.
- `background.js`: Background script that injects the content script into YouTube video pages when the tab is activated or updated.
- `content.js`: Content script that controls the play/pause state of YouTube videos based on tab visibility.
- `icons/`: Directory containing the extension's icons.

## Usage
Once installed, the extension will automatically pause any YouTube video you are watching when you switch to another tab and resume playing when you return to the YouTube tab. There are no additional configurations or settings needed.
