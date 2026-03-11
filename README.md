# Professional HTML5 MP3 Player

A beautiful, responsive, and zero-configuration MP3 player built with HTML, CSS, and Vanilla JavaScript.

## 🚀 Features
- **Premium Aesthetics**: Gradient animated backgrounds and Glassmorphism design.
- **Dynamic Playlist**: Automatically scans the `mp3s/` folder for `.mp3` files (Requires a Web Server).
- **Responsive**: Mobile-first design that works on phones, tablets, and desktops.
- **Audio Controls**: Play/Pause, Next/Previous, Progress bar, and volume (browser default).
- **Infinite Loading States**: Visual feedback with a spinner when tracks are buffering.

## 📂 Setup & Deployment
1. Upload `index.html` and the `mp3s/` folder to your web host.
2. Put your `.mp3` files into the `mp3s/` folder.
3. Ensure the `.htaccess` file is inside the `mp3s/` folder to allow the server to list the files (required for the automatic playlist).
4. Access `index.html` through your browser via `http://` or `https://`.

> [!IMPORTANT]
> This player **must** be run from a web server (live or local) to allow the dynamic playlist scanning to function. It will not list files when opened as a local file (`file:///...`).
