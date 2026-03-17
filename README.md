# Auto Video Merger (macOS) 🎥

A simple and fast shell script to automatically sort and merge `.mp4` files within a folder using **FFmpeg**. This script is designed for macOS users who want a quick way to join video clips in chronological order.

## Features ✨
* **Auto-Sort:** Groups and sorts all `.mp4` files by their creation time.
* **Lightning Fast:** Uses stream copying (`-c copy`), meaning no quality loss and near-instant merging.
* **Auto-Install:** Automatically detects if `ffmpeg` or `Homebrew` are missing and offers to install them for you. 🛠️

## How to Use 🚀

1. **Download the script:** Place `merge` into the folder containing your videos.
2. **Open Terminal:** Navigate to your folder:
   ```bash
   cd /path/to/your/video/folder
