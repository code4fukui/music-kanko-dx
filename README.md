# music-kanko-dx

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A self-contained, web-based music player for the "観光DX" (Tourism DX) playlist, featuring AI-generated music. This project runs directly in a web browser without needing a server.

## Demo

**[▶️ Live Demo](https://code4fukui.github.io/music-kanko-dx/)**

The user interface consists of three main panels: a playlist of songs, a central player with album art and track information, and a panel for lyrics. The page background is a blurred version of the current song's album art.


![Screenshot of the music-kanko-dx player interface](https://user-images.githubusercontent.com/10928/270018151-5121b61b-9993-4710-9289-e1377855b76b.png)


## Features

-   **Web-Based Player**: A simple and elegant music player that runs in any modern browser.
-   **Dynamic UI**: Displays album art, song metadata (prompt, tags), and full lyrics.
-   **Media Session API Integration**: Supports native OS media controls, allowing you to control playback from your lock screen, notification center, or connected devices like smartwatches and car stereos.
-   **Self-Contained**: After an initial data download, the player and all its assets can be run offline.
-   **Zero Dependencies**: The player itself is built with vanilla HTML, CSS, and JavaScript.

## Getting Started

To run this project locally, you first need to download the music and image assets.

### Prerequisites

-   [Deno](https://deno.land/) must be installed to run the download script.

### Setup

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/code4fukui/music-kanko-dx.git
    cd music-kanko-dx
    ```

2.  **Download the playlist assets:**
    Run the following command in the project root. This script will download all necessary audio and image files and create the `playlist.json` file.
    ```sh
    deno run -A https://code4fukui.github.io/music-opendata-fukui/download.js 9da471f6-0d33-4b2d-bbc1-4712fa3a7fb0
    ```

3.  **Open the player:**
    Open the `index.html` file in your web browser to start the music player.

## Data

The music, lyrics, and artwork for this playlist are sourced from the `music-opendata-fukui` project. The download script fetches assets associated with the playlist ID `9da471f6-0d33-4b2d-bbc1-4712fa3a7fb0`.

-   **Data Source**: [music-opendata-fukui](https://github.com/code4fukui/music-opendata-fukui)

The songs were originally generated using Suno AI.
