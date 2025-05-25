# Moodify - AI-Based Music Playlist Generator

<p align="center">
  <img src="assets/images/sonnetlogo.png" alt="Moodify Logo" width="120"/>
</p>


Moodify is an innovative Flutter app that generates personalized music playlists based on your mood using AI-powered recommendations and seamless Spotify integration.

---

## Features

- **AI-Powered Mood Detection:** Get music playlists tailored to your current mood using OpenAI's advanced language models.
- **Spotify Integration:** Authenticate with Spotify and create playlists directly in your Spotify account.
- **Custom OAuth Flow:** Secure and smooth authentication using custom URI schemes.
- **Fancy Loading Animations:** Engaging and modern UI with animated loading screens during playlist sync.
- **Cross-Platform Flutter App:** Works on Android and iOS with beautiful UI and smooth animations.
- **Playlist Management:** Search and add songs accurately to Spotify playlists with advanced search queries.

---

## Screenshots

<p align="center">
  <img src="assets/images/sonnet.png" alt="Home Screen" width="220"/>
  <img src="assets/images/playlist_screen.png" alt="Playlist Screen" width="220"/>
</p>


---

## Getting Started

### Prerequisites

- Flutter SDK 3.22.2 or later
- Spotify Developer Account with Client ID and Secret
- OpenAI API Key

### Installation

1. Clone the repository
2. Run `flutter pub get` to install dependencies
3. Add your Spotify and OpenAI credentials in a `.env` file:

    ```
    SPOTIFY_CLIENT_ID=your_spotify_client_id
    SPOTIFY_CLIENT_SECRET=your_spotify_client_secret
    OPENAI_API_KEY=your_openai_api_key
    ```

4. Configure AndroidManifest.xml and Info.plist for custom URI scheme `moodify://callback`
5. Run the app on your device or emulator

---

## Usage

- Launch the app and select your mood
- Tap the Spotify button to authenticate and create a playlist
- Enjoy your personalized playlist in Spotify

---

## Architecture

- Flutter frontend with clean separation of UI and business logic
- Uses REST APIs for OpenAI and Spotify
- Custom deep link handling with `app_links` package
- Modular and reusable components for loading animations and dialogs

---

## Future Enhancements

- Machine learning based personalized recommendations
- Social sharing and collaborative playlists
- Offline mode and caching
- Multi-platform support including web

---

## License

This project is licensed under the MIT License.

---

## Contact

For questions or feedback, contact Vivek Fatwani.
