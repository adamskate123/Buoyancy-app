# Does It Float? 🌊

An interactive buoyancy visualization for kids aged 5–7. Tap objects to drop them in the water and discover what floats and what sinks!

---

## Opening on Desktop

1. Download or clone this repository
2. Open the `index.html` file in any modern web browser (Chrome, Firefox, Safari, Edge)
   - **Option A:** Double-click `index.html` in your file manager
   - **Option B:** Drag `index.html` into an open browser window
   - **Option C:** Right-click `index.html` → "Open with" → choose your browser
3. The app loads instantly — no internet connection or installation required

---

## Opening on iOS (iPhone / iPad)

> **Note:** iOS treats `.html` files as plain text, so Safari will **not** appear in the share sheet when opening a file directly. Use one of the options below instead.

### Option 1 — Quick Look in Files app (easiest, no Wi-Fi needed)
1. Get `index.html` onto your device via AirDrop or iCloud Drive:
   - **AirDrop:** On your Mac, right-click `index.html` → Share → AirDrop → select your device
   - **iCloud Drive:** Copy the file to iCloud Drive on your Mac, then open the Files app on iOS
2. In the **Files** app, **long-press** `index.html`
3. Tap **Quick Look** from the menu that appears
4. The app will render and run fully inside the Quick Look preview

### Option 2 — Host locally over Wi-Fi (best experience)
1. Make sure your iPhone/iPad and computer are on the **same Wi-Fi network**
2. On your computer, open a terminal and run:
   ```
   cd /path/to/Buoyancy-app
   python3 -m http.server 8080
   ```
3. Find your computer's local IP address:
   - **Mac:** System Settings → Wi-Fi → Details → IP Address
   - **Windows:** Run `ipconfig` in Command Prompt, look for IPv4 Address
4. On your iPhone/iPad, open **Safari** and go to:
   ```
   http://192.168.1.5:8080
   ```
   *(replace `192.168.1.5` with your computer's actual IP)*

### Option 3 — Add to Home Screen (recommended for kids)
Once the page is open via Option 2:
1. Tap the **Share** button (box with arrow at the bottom of Safari)
2. Scroll down and tap **Add to Home Screen**
3. Tap **Add**

The app will appear as a full-screen icon on the home screen, just like a native app — no browser chrome, great for little hands!

---

## No installation required

This is a single HTML file with no external dependencies. Everything runs locally in the browser.
