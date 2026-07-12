# 🎬 [Silly Overlay] - Media Repository

This repository serves as the external media host for the Garry's Mod addon **[Silly Overlay]**.

Instead of packing large video files directly into the addon folder (which inflates the `.gma` file size and slows down server loading times for players), the addon fetches its video content directly from this repository via the web.

## ⚙️ How It Works

1. Videos are uploaded to the `videos/` directory in this repository.
2. The GMod addon uses in-game HTML/Web panels (like `Derma_HTML` or Awesomium/Chromium) to stream the videos.
3. Players get faster download times when joining the server, and the addon stays lightweight!
