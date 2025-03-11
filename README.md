# FTP M3U Playlist Generator

A desktop application that helps you create M3U playlists from FTP media servers. This tool allows you to search for movies and TV series across FTP directories and generate organized playlists for your media player.

****WARNING****

Ignore Flase Windows defender Flag

## Features

- **Easy FTP Navigation**: Search across FTP servers for your favorite movies and TV shows
- **Smart Search Algorithm**: Intelligently finds content even in complex directory structures
- **Season/Episode Detection**: Automatically organizes TV series by season and episode
- **Category Management**: Save, edit, and delete your favorite FTP server categories
- **Custom File Extensions**: Specify which file types to include in your playlists
- **Progress Tracking**: Real-time progress updates and detailed logging
- **User-Friendly Interface**: Simple and intuitive GUI for all experience levels

## Installation

### Windows Executable

1. Download the latest release from the [Releases](https://github.com/yourusername/ftp-m3u-generator/releases) page
2. Run the executable - no installation required!

### From Source

If you prefer to run from source:

```bash
# Clone the repository
git clone https://github.com/yourusername/ftp-m3u-generator.git

# Navigate to the directory
cd ftp-m3u-generator

# Install requirements
pip install -r requirements.txt

# Run the application
python FTP_m3u_Generator.py
```

## Requirements

- Python 3.6+
- Required packages:
  - requests
  - beautifulsoup4
  - tkinter (usually comes with Python)

## Usage

1. Launch the application
2. Select or enter an FTP server URL
3. Enter the name of the movie or TV series you want to find
4. Specify file extensions if needed (defaults to .mp4, .mkv, .avi)
5. Choose where to save your playlist
6. Click "Generate Playlist"
7. Open the generated .m3u file with your favorite media player

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Thanks to all contributors who have helped improve this tool
- Inspired by the need for better organization of media content from FTP servers

## Disclaimer

This tool is designed for use with legitimate FTP servers where you have proper access permissions. The developers are not responsible for any misuse of this software.
