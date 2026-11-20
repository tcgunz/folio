# Folio

PDF reader, editor and document scanner that runs in your browser.

Open it: https://tcgunz.github.io/folio/

---

© 2026 Tommy Chieng. All rights reserved. This is proprietary software. See [LICENSE](LICENSE).
Copying, modifying or redistributing any part of this code without written permission is not allowed.

## To do for the Play Store (Capacitor) build

- **Receipt reading: switch to Google ML Kit text recognition.** The web version reads receipts with Tesseract in the browser (several seconds per receipt, weaker on faded thermal paper). ML Kit runs on the phone, takes under a second, is much more accurate, works offline and needs no server. Swap it in where `rcWorker()` / `ocrReceipt()` are used in `index.html`.
- Save into the app's own Folio folder (Documents and Receipts subfolders).
- Google Drive sync.
