REPORT CARD SYSTEM - WINDOWS INSTALLER

1. Copy this entire folder to a Windows laptop/PC.
2. Install Node.js LTS from https://nodejs.org/ if Node.js is not already installed.
3. Double-click BUILD-WINDOWS.bat.
4. Wait for npm install to finish and then for electron-builder to finish.
5. Open the dist folder. The file named Report Card System Setup ...exe is the Windows installer.
6. Run the installer and follow the prompts. A desktop shortcut will be created.

The original HTML application is packaged unchanged as the renderer. The Electron wrapper provides the Windows desktop application shell. The HTML app already uses IndexedDB/localStorage fallbacks for offline storage and has backup/restore functions.
