# WashingtonPost Logger Extension

\#vibe-coded

⚠️ **WARNING: This extension is UNTESTED** ⚠️

This Firefox extension executes JavaScript code when visiting washingtonpost.com pages.

## Installation (Development Mode)

1. Open Firefox
2. Navigate to `about:debugging`
3. Click "This Firefox" in the left sidebar
4. Click "Load Temporary Add-on..."
5. Select the `manifest.json` file from this directory
6. The extension will be loaded temporarily (removed on Firefox restart)

## What it does

- Runs automatically when visiting any `*.washingtonpost.com` page
- Executes the code in `content.js` on page load

## Development Notes

- This is a temporary extension for development/testing purposes
- Extension will be removed when Firefox is restarted
- Use Firefox Developer Tools (F12) → Console to see output
- No permanent installation - only for debugging/development use