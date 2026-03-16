# music-kanko-dx

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A music player for an open data project about tourism in Fukui, Japan.

## Demo
The project is hosted at https://code4fukui.github.io/music-kanko-dx/

## Features
- Plays a music playlist related to tourism in Fukui
- Shuffles and reorders the playlist in various ways
- Displays song metadata, lyrics, and album artwork
- Supports the Media Session API for control from external devices

## Requirements
This project requires the [Deno](https://deno.land/) runtime to download and run the music files.

## Usage
To download and run the project:

```sh
deno -A https://code4fukui.github.io/music-opendata-fukui/download.js 9da471f6-0d33-4b2d-bbc1-4712fa3a7fb0
```

Then open the `index.html` file in a web browser.

## Data / API
This project uses the [music-opendata-fukui](https://github.com/code4fukui/music-opendata-fukui) open data project to fetch the music files and metadata.

## License
MIT License — see [LICENSE](LICENSE).

## Preserved Notes
## download
with [music-opendata-fukui](https://github.com/code4fukui/music-opendata-fukui)
