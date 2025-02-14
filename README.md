# Meme Sharing App

## Overview
Meme Sharing App is a simple Android application that fetches random memes from the internet and allows users to share them with friends. The app uses the **Meme API** to retrieve memes and displays them in an easy-to-use interface.

## Features
- Fetches random memes from an API.
- Displays memes using **Picasso** for smooth image loading.
- Allows users to fetch a new meme with the **NEXT** button.
- Users can share memes via social media or messaging apps.

## Tech Stack
- **Language**: Kotlin
- **API**: [Meme API](https://meme-api.com/gimme)
- **Libraries**:
  - [Volley](https://developer.android.com/training/volley) for API requests
  - [Picasso](https://square.github.io/picasso/) for image loading
  
## Screenshots
![image](https://github.com/user-attachments/assets/34eeb05f-e666-4b89-9649-2562537dece2)


## How It Works
1. The app fetches a meme from the API on launch.
2. Clicking **NEXT** fetches a new meme.
3. Clicking the **Share** button allows users to share the displayed meme.

## Code Structure
- **MainActivity.kt**: Handles UI and API requests.
- **activity_main.xml**: UI layout for the app.
- **AndroidManifest.xml**: App permissions and settings.

## Permissions Required
- **Internet Access**: To fetch memes from the API.
- **Write External Storage**: To save and share memes.


Enjoy sharing memes! 🚀



