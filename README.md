# Glinx

A friendly, responsive social-networking prototype — a little place to find your people, share moments, and stay close across the miles.

## Run it

This is a static website. Open `index.html` in a browser, or serve this directory with any static web server (for example, `python -m http.server 8000`). No build step or dependencies are required.

## Included in the prototype

- Sign-up and sign-in screens with a welcoming responsive interface.
- Home feed with sample posts, appreciation, comments, search, and post composer.
- Photo/video file selection, people discovery, follow buttons, stories, and circle navigation.
- Friend conversations, demo messaging, call UI entry points, notifications, and dark mode.
- Local browser storage for demo profile, posts, following, and conversations.

## Important security and product notes

This repository is a **front-end prototype**, not a production social network. Demo accounts and posts are stored in the browser. The demo sign-in does not provide secure authentication; do not use real or reused passwords, and do not enter sensitive personal information. The administrator email shown in the request (`gilenyajnr@gmail.com`) is only used as a display/demo identifier. No password, secret, or privileged admin credential is embedded in the code.

Real accounts, secure admin authorization, cross-device posts/media, real-time chat, and audio/video calls require a backend and trusted providers (for example, managed authentication, a database/object store, WebSockets, and a WebRTC calling service). Client-side screens alone do not enable real calling or messaging between users.

## Files

- `index.html` — app layout and sign-in/sign-up UI
- `styles.css` — responsive visual design
- `app.js` — interactive demo behavior
