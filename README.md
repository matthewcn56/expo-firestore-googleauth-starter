# Quick Starter For Expo Apps!

This is a quick and easy template repository you can use to get up and running with expo managed workflows connected to firestore and firebase!

# What Do I Need To Do To Get Started?

- First, set up your app on the Firebase Console.
- Set Up your app on the Googl Cloud Console.
- Link Firebase to Your Web Application, Enable Google Sign In
- Set Up Your Google OAuth Clients on The Google Cloud Console
- Attach Your Google OAuth Clients To The Firebase App
- Replace ApiKeys with your info as appropriate within `./config/apiKeys.js`
- `cd quickstarter` and `npm install`
- `expo start` and start making your app!

# What does this app contain?

- Since this is just a guide app, it only contains a login screen, a home page, and two other pages connected via a stack navigator.
- With Hooked React Components, the user's profile is stored within `AuthContext`.
- When new users sign in for the first time, the firestore database gets updated and stores their display name, their gmail photo, and the resulting UID!

# Why Create This?

Every complex app idea has to start somewhere, and this takes away a lot of the brunt work of having to set-up the barebones of an app yourself!
