# Audio Clipper

A simple web application to extract custom regions from audio files using WaveSurfer.js.

## Features

- 📁 Drag-and-drop or click to upload audio files
- 🎵 Visual waveform display using WaveSurfer.js
- 🖱️ Interactive region selection - drag on the waveform to select any portion
- ▶️ Playback controls with time display
- ✂️ Extract selected regions from your audio
- ⬇️ Download extracted audio as compressed MP3 format (128 kbps)
- 🎨 Beautiful, modern UI with gradient background

## Supported Formats

- MP3
- WAV
- OGG
- M4A
- AAC
- FLAC
- MP4 (audio extraction)
- And other audio formats supported by the browser

## Usage

1. Open `index.html` in a modern web browser
2. Drag and drop an audio file onto the drop zone, or click to browse
3. The waveform will display showing your audio
4. **Drag on the waveform** to select the region you want to extract
5. Adjust the region by dragging the edges (handles appear on hover)
6. Double-click the region to preview it
7. Click **"Extract Selection"** to prepare the selected audio
8. Click **"Download"** to save the extracted region as MP3
9. Click **"Load New File"** to start over with a different file

**Tips:**
- Click the play button to listen to the full audio
- Only one region can be selected at a time
- The selection info shows start time, end time, and duration

## Technical Details

- Uses WaveSurfer.js v7 for audio visualization
- WaveSurfer Regions plugin for interactive region selection
- Pure client-side processing (no server required)
- Web Audio API for audio manipulation
- lamejs library for MP3 encoding
- Exports extracted audio as MP3 format (128 kbps bitrate)
- Typical file size: ~1MB per minute of audio

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
