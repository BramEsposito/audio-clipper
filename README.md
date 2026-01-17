# Audio Clipper

A simple web application to trim 10 seconds from the end of audio files using WaveSurfer.js.

## Features

- 📁 Drag-and-drop or click to upload audio files
- 🎵 Visual waveform display using WaveSurfer.js
- ✂️ Automatically trim 10 seconds from the end of audio files
- ⬇️ Download the trimmed audio as WAV format
- 🎨 Beautiful, modern UI with gradient background

## Supported Formats

- MP3
- WAV
- OGG
- And other audio formats supported by the browser

## Usage

1. Open `index.html` in a modern web browser
2. Drag and drop an audio file onto the drop zone, or click to browse
3. The waveform will display showing your audio
4. Click "Trim 10 Seconds" to remove the last 10 seconds
5. Click "Download Trimmed Audio" to save the result
6. Click "Load New File" to start over with a different file

## Technical Details

- Uses WaveSurfer.js v7 for audio visualization
- Pure client-side processing (no server required)
- Web Audio API for audio manipulation
- Exports trimmed audio as WAV format

## Requirements

- Modern web browser with Web Audio API support
- No installation or build process required
- Just open the HTML file in your browser

## Deployment to GitHub Pages

To deploy this application to GitHub Pages:

1. Go to your GitHub repository: https://github.com/BramEsposito/audio-clipper
2. Click on **Settings** tab
3. Scroll down to **Pages** section in the left sidebar
4. Under **Source**, select the branch `claude/audio-trim-wavesurfer-Q6mCg`
5. Keep the folder as `/ (root)`
6. Click **Save**
7. Wait a few minutes for GitHub to build and deploy
8. Your site will be available at: https://bramesposito.github.io/audio-clipper/

Note: If you don't see the branch in the dropdown, make sure it has been pushed to GitHub.

## Live Demo

Once deployed to GitHub Pages, visit the URL above. Alternatively, open `index.html` locally in your browser.
