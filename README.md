# Resilinet-app
Community resilience and local alerts app built with React Native + Firebase
# ResiliNet Starter (Expo + Firebase)

Quick start:
1. Install Expo CLI: `npm install -g expo-cli`
2. Create a Firebase project and enable Email/Password auth and Firestore.
3. Copy `firebaseConfig.js` and paste your Firebase config.
4. Install dependencies: `npm install`
5. Start the app: `npm run start`

Admin web app:
- `npm run admin:start` to run a minimal admin UI to publish verified alerts/POIs.

Firestore collections used:
- `alerts` (documents: title, message, location {lat,lng}, verified:boolean, createdAt, postedBy)
- `posts` (help board offers/requests: type, title, body, location, contact, status)
- `users` (profile metadata)
- `messages` (simple chat threads)
