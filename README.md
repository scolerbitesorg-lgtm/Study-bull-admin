# Study Bull Preview Prototype

## Files
- `index.html` — single-file, mobile-friendly interactive preview. Open it in a browser to test the UI.

## Important
This is a prototype only. It uses sample content embedded in the HTML. It does **not** include a real admin login, Firebase connection, cloud sync, or secure publishing.

## Prompt for Google AI Studio
Keep the current Study Bull user-app UI and working preview. Build a separate, mobile-friendly Admin Panel that manages the content shown in the user app. Admin should be able to add/edit/delete/reorder home buttons; create subjects and nested folders; add/edit/delete Quiz, MCQ, Mock Test, and Notes content inside folders; and publish changes so the user app reads the latest content. Keep the existing Calculation button and its behavior unchanged. Start with a clean, empty Firebase database for all other content—do not import or recreate old sample data. Use Firebase Authentication for admin access and Firestore with proper security rules; never expose admin write permissions to ordinary users. Keep the user app and admin panel modular, and explain the exact files changed. Do not claim Firebase is connected unless you actually configure and test it. Preserve a working preview and do not redesign unrelated parts of the UI.

## Preview
Open `index.html` directly in a browser. Quiz and mock test have small demo questions; notes and subjects are examples only.
