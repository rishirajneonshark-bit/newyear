# A Little Universe birthday website

## Run
Install Node.js 18+, open this folder in VS Code, then run:

```bash
npm install
npm run dev
```

## Add photos
Put your images in `public/photos/` and edit the `photos` array near the top of `src/App.jsx` to match the exact filenames and captions. PNG/JPG/WEBP are supported when the extension matches.

## Add background music
Open `src/App.jsx` and replace `PASTE_YOUR_CLOUDINARY_AUDIO_URL_HERE` in the `MUSIC_URL` constant with your Cloudinary audio delivery URL. Music starts when the visitor clicks **Open your surprise**. The Sound button in the header toggles playback, and the track loops across all scenes.

## Personalise
Edit the `notes` array, `wishes` array and letter text in `src/App.jsx`. Change “beautiful human” to her name or nickname.

## Deploy
Run `npm run build`; deploy the `dist` folder to Vercel. Build command: `npm run build`; output directory: `dist`.
