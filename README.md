# AR.js Nav + Draw Demo (Hiro Marker)

A tiny AR.js demo you can show on **desktop and mobile** using **GitHub Pages**. It has:

- **Nav Mode:** a 3D arrow on the HIRO marker that points to a chosen target (N/E/S/W), draws a path, and shows distance + heading.
- **Draw Mode:** tap on the marker’s plane to place dots and auto-connect lines — simple AR sketching.

## Live Demo (after deployment)
https://YOUR-USERNAME.github.io/arjs-nav-draw-demo/

> Replace `YOUR-USERNAME` with your GitHub handle.

## How to Run (Step-by-Step)

1. **Get the Hiro marker**  
   Print or open on another screen a standard **Hiro marker** (black square with a bold white Kanji).  
   _Search for “AR.js Hiro marker png” and use the official one._

2. **Open the demo (HTTPS)**  
   Use the GitHub Pages link on **Chrome/Edge/Firefox (Android)** or **Safari (iOS)**.  
   Allow camera access. Point your camera at the Hiro marker.

3. **Use it**  
   - **Nav Mode** (default): Tap **North/East/South/West** to change the destination.  
     The arrow rotates, path updates, and “Heading | Distance” text appears.  
     When you’re very close, the target pulses green.  
   - Tap **Mode: Nav** to switch to **Draw**. Now tap the marker plane to drop dots; lines auto-connect for a simple “AR draw.”  
   - Tap **Clear** to reset drawings and nav.


## Technology
- **A-Frame** for 3D
- **AR.js (marker-based)** for AR
- **MeshLine** to draw path/segments

## Troubleshooting
- **Nothing shows?**  
  - Ensure **camera permission** is allowed.  
  - Use **HTTPS** (GitHub Pages) on mobile.  
  - Keep the **whole Hiro marker** in the frame with **good lighting**.  
  - Try moving closer/farther; avoid reflections.
- **iOS Safari** requires HTTPS. Use the GitHub Pages link, not `file:///`.
- **Desktop testing** works: show the Hiro marker on another phone/tablet screen or print it.

## Credits
Built with ❤️ using A-Frame + AR.js.

