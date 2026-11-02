# JAY-AGENCY

Static website for Jay's Agency, configured for Firebase Hosting.

## Publish on Google

1. Create or select a Google Firebase project and enable Firebase Hosting.
2. Install Node.js, then authenticate with the Firebase CLI:

   ```sh
   npx firebase-tools login
   ```

3. From this repository's root, deploy to the project:

   ```sh
   npx firebase-tools deploy --only hosting --project YOUR_FIREBASE_PROJECT_ID
   ```

Replace `YOUR_FIREBASE_PROJECT_ID` with the project you own or are authorized
to deploy to. Firebase Hosting will print the public website URL after a
successful deployment. This repository intentionally does not select or bind a
Google project.

Publishing makes the website publicly reachable; it does not guarantee that
Google Search will index it. Search indexing can be requested separately in
Google Search Console after the site is live.