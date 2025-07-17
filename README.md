<img width="1920" height="871" alt="image" src="https://github.com/user-attachments/assets/c23b24a6-2030-4522-992b-808c8c57cb72" /># Music Player

A modern music player web application built with vanilla JavaScript and CSS.  
Features include music search, cover display, lyrics, seekbar, equalizer visualization, and playlist slider.

## Features

- **Music Search:** Search by title, artist, or genre. Results update live as you type.
- **Cover & Lyrics:** Displays album cover and lyrics for the selected track.
- **Audio Player:** Play, pause, and seek through tracks. Shows current time and duration.
- **Equalizer Visualization:** Animated equalizer around the cover image.
- **Playlist Slider:** Browse and select tracks using a horizontal slider.
- **Responsive UI:** Designed for desktop use with a clean, dark theme.

## Folder Structure

```
public/
  covers/         # Album cover images
  img/            # Play/pause icons
  musics/         # Music files (.mp4)
src/
  js/             # JavaScript modules
  style.css       # Main styles
  seekbar.css     # Seekbar styles
index.html        # Main HTML file
```

## How to Run

1. Clone the repository.
2. Place your music files in `public/musics/` and cover images in `public/covers/`.
3. Open `index.html` in your browser or use a local server (recommended for fetch and module support).
4. for runing enter (npm run dev) in your terminal to run it on your local host but at first you most download the project files.

## Main Modules

- `main.js` – Loads music data and initializes modules.
- `searchmusics.js` – Handles search input, results, and click events.
- `slider.js` – Manages the playlist slider and music selection.
- `audio.js` – Audio playback logic and equalizer data.
- `handlemusicclicke.js` – UI updates for play/pause and equalizer animation.
- `seekbar.js` – Seekbar and time display logic.
- `Equlaizer/` – Equalizer visualization components.

## Customization

- Add new music files to `public/musics/` and update your music data source.
- Change styles in `src/style.css` and `src/seekbar.css`.
- Update cover images in `public/covers/`.

## Credits

Developed by Hesam Mohammadi.
E-mail:hsammhmdy940@gmail.com
phone Number:+989332372332

---

**Note:** For best results, use a local server (such as [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
https://drive.google.com/drive/folders/1_5FldLi9Zqb2LbNiC6lCZ1G9a_IBkRGP?usp=sharing
Download music of this link and put file in public folder.
