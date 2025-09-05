# YouTube Audio Downloader with GUI

## Overview
A Python GUI application for downloading YouTube videos and playlists as MP3 audio files. Built with tkinter for the interface and yt-dlp for downloading functionality.

## Recent Changes (September 4, 2025)
- Created a complete GUI application from existing command-line YouTube downloader
- Added playlist download functionality
- Integrated all audio format selection options (best, worst, custom bitrate)
- Added progress tracking and real-time logging
- Configured workflow to run the GUI application

## Project Architecture
- `main.py` - Main GUI application using tkinter
- `attached_assets/yt_1757024145517.py` - Original command-line version (reference)
- Dependencies: yt-dlp, tkinter (built-in), ffmpeg

## Features
- Single video and playlist downloads
- Audio quality selection (best, worst, custom bitrate)
- MP3 output with configurable quality (128k, 192k, 256k, 320k)
- Custom output directory selection
- Real-time progress tracking and logging
- Thread-safe GUI operations

## User Preferences
- Simple, easy-to-use GUI interface
- Support for both single videos and playlists
- Integrated quality selection without complex menus