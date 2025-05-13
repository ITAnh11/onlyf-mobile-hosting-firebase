# Firebase Hosting Setup

This guide will help you set up Firebase Hosting for your project.

## Prerequisites

1. Install [Node.js](https://nodejs.org/) and npm.
2. Install the Firebase CLI:
   ```bash
   npm install -g firebase-tools
   ```
3. Log in to Firebase:
   ```bash
   firebase login
   ```

## Steps to Set Up Firebase Hosting

1. **Initialize Firebase in Your Project**:

   ```bash
   firebase init
   ```

   - Space to select (Hosting: Configure files for Firebase Hosting and (optionally) set up GitHub Action deploys) -> enter
   - Choose your project
   - Choose the public directory (`public`).
   - Configure as a single-page app (rewrite all urls to /index.html)? N
   - Set up automatic builds and deploys with GitHub? N
   - File public/index.html already exists. Overwrite? N

2. **Deploy to Firebase Hosting**:
   ```bash
   firebase deploy
   ```

## Additional Resources

- [Firebase Hosting Documentation](https://firebase.google.com/docs/hosting)
- [Firebase CLI Reference](https://firebase.google.com/docs/cli)
