# Lead Tracker - Chrome Extension

A lightweight Chrome browser extension for tracking and managing leads by saving URLs. Perfect for sales professionals, marketers, and anyone who needs to quickly capture and organize web links.

## Features

- **Manual URL Input**: Save leads by typing URLs directly into the extension
- **One-Click Tab Capture**: Instantly save the URL of your current browser tab with a single click
- **Persistent Storage**: All saved leads are stored locally in your browser using localStorage, so they persist across sessions
- **Easy Management**: View all saved leads as clickable links in a clean list interface
- **Quick Deletion**: Double-click the delete button to clear all saved leads at once

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/lead-tracker.git
   cd lead-tracker
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Build the extension (if needed):
   ```bash
   npm run build
   ```

4. Load the extension in Chrome:
   - Open Chrome and navigate to `chrome://extensions/`
   - Enable "Developer mode" (toggle in the top right)
   - Click "Load unpacked"
   - Select the project directory

## Usage

1. Click the extension icon in your Chrome toolbar to open the popup
2. **Save a lead manually**: Type a URL in the input field and click "SAVE INPUT"
3. **Save current tab**: Click "SAVE TAB" to capture the URL of the currently active tab
4. **View leads**: All saved leads appear as clickable links in the list below
5. **Delete all leads**: Double-click the "DELETE ALL" button to clear all saved leads

## Technical Details

- **Manifest Version**: 3 (latest Chrome extension standard)
- **Storage**: Uses browser localStorage API for data persistence
- **Permissions**: Requires "tabs" permission to capture current tab URLs
- **Build Tool**: Vite for development and building

## Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript
- Chrome Extensions API
- Vite

## Project Structure

```
lead-tracker/
├── index.html          # Extension popup HTML
├── index.css           # Styling
├── index.js            # Main application logic
├── manifest.json       # Chrome extension manifest
├── icon.png            # Extension icon
└── package.json        # Project dependencies
```

## License

This project is open source and available for personal and commercial use.
