# Lottie Inspector

A browser tool for previewing and editing Lottie animations exported from After Effects with Bodymovin.

- Drop a Bodymovin export `.zip` or a Lottie `.json` to preview it
- Edit text, swap images, and recolor shapes, solids and text
- Change any color everywhere at once from the palette
- Export the edited animation as a single JSON with images embedded

Everything runs in your browser. Files are never uploaded.

## Project structure

- `public/index.html`: the whole tool in one file
- `wrangler.jsonc`: tells Cloudflare to serve the `public` folder
