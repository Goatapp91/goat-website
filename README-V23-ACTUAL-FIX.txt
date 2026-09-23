V23 built directly from the user's current goat-website-main(2).zip.
Root cause found: app-v15.js referenced assets/normalized/<lang>/*.png, but the uploaded GitHub ZIP contained NO assets/normalized directory.
Fix: generated 42 real PNG files inside the already-existing assets/lang/<lang>/ folders and rewired GOAT_ASSET_MAP to those exact files. Cache version updated.
