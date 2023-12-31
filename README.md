# Chat App

## Objective

The objective was to build a chat app for mobile devices with **React Native**.
<br>
The app will provide users with a chat interface and options to share images and their location from a phone as well as the Android Simulator.

<br>
<p align="center"><sub>Chat App Screenshot gif</sub></p>
<br>

<p align="center"><img src="https://github.com/ilsegaertner/chat-app/blob/main/assets/gif%20for%20chat%20app.gif" alt="Screenshot 2, gif of the apps functionality" width="220">
</p>

<br>

## Features

- Select the background of the chat(four colors to choose)
- Sign-in and anonymous authentication with a username
- Sending/receiving messages in real-time
- images/location sharing
- Offline viewing of cashed messages

## Technologies used

- React Native
- Expo
- Google Firebase and Storage
- AsyncStorage cashing for offline usage
- Gifted Chat Library

## Directions for setting up the environment

- Install <a href="https://nodejs.org/en/learn/getting-started/how-to-install-nodejs">Node JS</a> on your device
- In the terminal: Install Expo globally: `npm install -g expo-cli`
- Sign up for an <a href="https://expo.dev/">Expo Account </a> to be able to run the app on your device
- Clone this repository
- Navigate to the folder and run `npm install`
- Use your own Firebase configuration code:
  - Sign in at [Google Firebase](https://firebase.google.com/)
  - **Create a Project** (uncheck **Enable Google Analytics for this project**)
  - **Create Database** in **Firestore Database** (choose a close region from the dropdown, and **Start in production mode**)
  - Change `allow read, write: if false;` to `allow read, write, if true;` in **Rules** tab
  - **Register app(`</>`)** in **Project Overview**
  - Now, follow the provided directions of adding Firebase SDK:
    - Install firebase: `npm install firebase`
    - Initialize firebase: Copy and paste the provided Firebase configuration and change them in the _App.js_ of the downloaded repository
- Download Android Studio(Win) or iOS Simulator/XCode(Mac)
- Run `expo start` in the terminal. Follow the instruction to access the app via the iOS Simulator/Android Emulator

## Screenshots

<img width="220" alt="Screenshot 1 from app" src="https://github.com/ilsegaertner/chat-app/blob/main/assets/screen1.png"> <img width="220" alt="Screenshot 2 from app" src="https://github.com/ilsegaertner/chat-app/blob/main/assets/screen-example.png"><img width="220" alt="Screenshot 3 from app" src="https://github.com/ilsegaertner/chat-app/blob/main/assets/screen-example2.png">
