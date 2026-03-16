# Encoder-Decoders

Small browser-based demos for encoding and decoding text in two different formats:

- `Text <-> RGB Pixel Encoder`: stores text bytes directly inside PNG pixel RGB channels.
- `Text <-> WAV Audio Encoder`: converts text into audio tones and decodes tones back into text.

## Live Deployment

Open the deployed project here:

[https://omerbhatti.github.io/encoder-decoders/index.html](https://omerbhatti.github.io/encoder-decoders/index.html)

## Pages

- `index.html`: landing page linking to both tools.
- `text-to-rgb.html`: text to PNG encoder/decoder (canvas + uploaded image decoding).
- `text-to-wav.html`: text to audio modem encoder/decoder (playback, WAV download, mic/file decode).

## How To Use

1. Open `index.html` (or the deployed URL) and choose a tool.
2. Enter or edit text in the input area.
3. Encode, then decode from the generated output (or uploaded file) to verify round-trip conversion.

## Run Locally

No build step is required. These are static HTML files.

- Option 1: open `index.html` directly in your browser.
- Option 2: serve the folder with any static server (recommended for microphone/file workflows).
