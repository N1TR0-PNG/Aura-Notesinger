# aura-notesinger
Aura Music + Aura Codex under one shell, with Google sign-in and Firestore cloud snapshots.

    npm install
    npm run dev                 # local
    firebase login && npm run deploy

Enable in the Firebase console: Authentication -> Google, Firestore database.
Service account keys (admin SDK) are server-only: see scripts/admin-init.js, never commit them.
