## 🛠️ Installation & Setup

### 1. Clone the Repository
```bash
git clone [https://github.com/SURYAPRAKASHKALYANAM/Fahhhh-Leetcode.git](https://github.com/SURYAPRAKASHKALYANAM/Fahhhh-Leetcode.git)
cd Fahhhh-Leetcode

```

### 2. Prepare the Directory

Ensure your local folder structure matches the following:

* `/sounds`
* `manifest.json`
* `content.js`
* `popup.html`
* `popup.js`
* `icon128.png` (and other sizes)

### 3. Load the Extension

1. Open your browser and navigate to `chrome://extensions/`.
2. Enable **Developer mode** (toggle in the top-right corner).
3. Click **Load unpacked** and select your `Fahhhh-Leetcode` project folder.

### 4. Critical First Step

* Open any [LeetCode Problem](https://leetcode.com/problems/).
* **Click anywhere on the page once.** Modern browsers like Brave and Chrome block audio until the user interacts with the page.

---

## 📁 Project Structure

```text
├── sounds/             # Directory containing 22 meme .mp3 files
├── icon16.png          # Toolbar icon
├── icon48.png          # Extensions menu icon
├── icon128.png         # Main store/display icon
├── manifest.json       # Extension configuration (Manifest V3)
├── content.js          # Logic for monitoring LeetCode result DOM
├── popup.html          # The Settings UI (HTML/CSS)
└── popup.js            # Logic for Meme Selection and Audio Previews

```

---

## 🤝 Contributing
Feel free to fork this repository, add new sounds to the `/sounds` folder, and update the `memeNames` object in `popup.js`.

**Happy Coding!** 💻🔥
