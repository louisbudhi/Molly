⚡ Molly AI Assistant 💬

Molly is a versatile, single-file AI chat application designed to be a personal assistant, deep search engine, and market analyst. It uses Google's Gemini API for intelligence and Firebase for persistent user login and chat history.

✨ Key Features

Deep Research: Real-time, citation-backed answers via Google Search grounding.

Multimodal: Analyze uploaded images and documents.

Persistent History: Saves chats using Google Firebase Firestore.

User Accounts: Secure Login/Register via Email/Password or Google Sign-In.

Customization: Includes Dark Mode and profile picture options.

🚀 Quick Start Setup

Molly runs entirely from one molly_ai.html file, but requires credentials to function.

1. Configure AI Key (Gemini)

Obtain your free Gemini API key from the Google AI Studio.

Find the const apiKey = "..." line in the HTML file's <script> block and paste your key.

2. Configure Backend (Firebase)

Create a project in the Firebase Console and add a Web App.

Copy the firebaseConfig = { ... } object provided by Firebase.

Paste this object into the corresponding placeholder in the HTML file's <script> block.

3. Enable Services

You MUST enable these in your Firebase Console project:

Authentication: Enable the Email/Password and Google providers.

Firestore Database: Click Create Database and select Start in Test Mode.

🌐 Deployment (Running the App)

Once configured, simply upload the single molly_ai.html file to any static hosting service.

Fastest Option: Use Netlify Drop (https://app.netlify.com/drop). Drag the file to get an instant, shareable URL.

Mobile Access: Open the public URL on your phone and use "Add to Home Screen" for an app-like experience.
