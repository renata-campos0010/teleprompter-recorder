# Teleprompter Recorder

A single-page tool I designed and built with Claude (AI) to record application videos while reading a script that scrolls right under the camera.

## What it does
- Scrolling teleprompter with adjustable speed, text size and column width (keyboard shortcuts shown next to each control)
- Live camera preview you can drag and resize, with microphone and camera selection and a volume meter
- Background options: blur, solid colors or your own image (uses MediaPipe Selfie Segmentation)
- Records video and audio in the browser, shows a time goal (green inside the target, red when over), and lets you watch the result before choosing Retake or Save
- Edit the script, job code and time goal directly on the page; everything is saved in your browser

## How to use
1. Download `index.html` and open it in Google Chrome.
2. Click **Turn on camera** and allow camera and microphone.
3. Click **Edit text**, paste your script and click **Save text**.
4. Press **Record** (or Enter), read, and press **Stop**.

Everything runs locally in the browser. No video is uploaded anywhere.

## Why I built it
I wanted a simple way to record short videos for job applications without looking like I was reading. I described what I needed, tested each version and asked for changes (draggable camera, background blur, microphone picker, editable text) until it worked the way I wanted.
