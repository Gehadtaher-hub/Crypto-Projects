FOLDER PLACEMENT

Create this structure:

project-folder/
  public/
    index.html
    firebase-config.js
  functions/
    index.js
    package.json
  firebase.json
  database.rules.json
  .firebaserc

Rename files after download:
- functions-index.js -> functions/index.js
- functions-package.json -> functions/package.json
- firebaserc.txt -> .firebaserc

SETUP
1. Register the Firebase Web App.
2. Paste its config into public/firebase-config.js.
3. Enable Authentication > Anonymous.
4. Create Realtime Database.
5. Install Firebase CLI: npm install -g firebase-tools
6. In functions/: npm install
7. From project-folder/: firebase login then firebase deploy

IMPORTANT
Student names and IDs are personal data. Share only with the course, state why data is collected, and delete records after the registration/project period.
