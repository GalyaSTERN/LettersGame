# Letters Game


## How to Use

### Online Access
1. Make sure your phone is on the same WiFi network as the computer running the app
2. Open a browser and go to: `http://YOUR_COMPUTER_IP:8000`
3. Tap anywhere on the screen to get a new letter and image

### Installation as App

**On iPhone:**
1. Open Safari and go to the app URL
2. Tap the **Share** button
3. Tap **Add to Home Screen**
4. Tap **Add**

**On Android:**
1. Open Chrome and go to the app URL
2. Tap the **menu** (three dots)
3. Tap **Install app** or **Add to Home screen**

## Local Setup

1. Clone this repository
2. Install Python (if you don't have it)
3. Navigate to the project folder
4. Run: `python -m http.server 8000`
5. Open your browser to `http://localhost:8000`

## Handshape Images

The app uses 64 handshape images from the [Global Signbank](https://github.com/Signbank/Global-signbank) project's media/handshapes directory.

## Files

- `index.html` - Main app HTML, CSS, and JavaScript
- `manifest.json` - PWA manifest for app installation
- `service-worker.js` - Service worker for offline support
- `images/` - Directory containing all handshape images

## License

This project uses handshape images from Global Signbank which are available under their respective licenses.
