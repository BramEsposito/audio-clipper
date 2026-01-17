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

## Live Demo

Simply open `index.html` in your browser to start using the application.
