# Cookie Generator

A tool for generating Netscape-format cookie files from browser sessions.

## Description
Cookie Generator is a user-friendly desktop application that allows you to generate cookie files from browser sessions. The tool creates a dedicated Chrome profile for each domain, making it easy to maintain separate sessions and export cookies in Netscape format.

## Requirements
- Windows Operating System
- Google Chrome Browser (must be installed)
- Internet Connection

## Installation
1. No installation required - just download and run `Cookie Generator.exe`
2. On first run, Windows may show a security warning - click "More info" and then "Run anyway"

## How to Use
1. Launch `Cookie Generator.exe`
2. Enter the website URL you want to generate cookies for
3. Choose where to save the cookie file using the "Browse" button
4. Click "Start Browser" - a new Chrome window will open
5. Log in to the website in the opened browser
6. After logging in, return to Cookie Generator and click "Login Complete"
7. Your cookie file will be saved to the selected location

## Features
- Dark mode interface
- Automatic cookie file naming based on domain
- Separate browser profiles for different domains
- Netscape cookie format support
- Session persistence between runs

## Troubleshooting
- **Browser won't start**: Make sure Google Chrome is installed
- **Grey/disabled buttons**: Follow the steps in order (you need to start browser before using "Login Complete")
- **Cookie file not generating**: Ensure you have write permissions in the selected directory
- **"Failed to create browser session"**: Check if you have enough disk space for browser profiles

## Technical Details
- Cookie files are saved in Netscape format
- Browser sessions are stored in `browser_sessions` folder in the same directory as the executable
- Each domain gets its own Chrome profile to prevent session conflicts

## Notes
- Keep your Chrome browser updated
- Don't close the Chrome window until after clicking "Login Complete"
- Each domain's cookies are saved in a separate file

## Support
This is a standalone tool. For issues or questions, contact the developer.

## Disclaimer
Use this tool responsibly and in accordance with websites' terms of service. The developer is not responsible for any misuse of this application.
