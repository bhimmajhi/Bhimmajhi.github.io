# Bhim Majhi — Portfolio + Firebase Live Gallery

## Folder structure
```
├── index.html            # public site
├── admin.html            # upload / login page
├── css/                  # style.css, admin.css
├── js/
│   ├── app.js            # public real-time gallery
│   ├── admin.js          # login + upload logic
│   ├── particles.js
│   └── config/           # firebase-config.js, cloudinary-config.js
├── assets/
│   ├── fonts/            # Destoria-Free.*
│   └── images/           # logo.png, photo1.jpg, photo2.jpg
├── firebase/             # firestore.rules, storage.rules
├── robots.txt, sitemap.xml
├── googleee67e686a31af878.html, pinterest-a95a6.html   # site verification (keep in root)
└── LICENSE
```

## One-line commands
Run locally:
```
python3 -m http.server 8000
```
Deploy to GitHub Pages:
```
git add -A && git commit -m "update" && git push
```

## Firebase setup (once)
1. Authentication → enable Email/Password, create admin user.
2. Create Firestore Database and Storage.
3. Paste `firebase/firestore.rules` and `firebase/storage.rules` into the Rules tabs and Publish.

Upload new posts from `/admin.html`; the public site updates in real time.
