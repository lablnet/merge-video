# Auto Video Merger (macOS) 🎥
A simple and fast shell script to automatically sort and merge `.mp4` files within a folder using **FFmpeg**. This script is specifically optimized for macOS and is perfect for joining video clips together quickly.
## Features ✨
* **Auto-Sort:** Automatically groups all `.mp4` files and sorts them by their creation/modification time.
* **Newest First Option:** Use the `--last` flag to put your most recent video at the start of the merge.
* **Lightning Fast:** Uses stream copying (`-c copy`), meaning zero quality loss and near-instant merging.
* **Auto-Install:** Automatically detects if `ffmpeg` or `Homebrew` are missing and offers to install them for you. 🛠️
* **macOS Compatible:** Built to work with Apple's default Bash version (3.2+).
## How to Use 🚀
1.  **Download & Place**: Put the `merge` script into the folder containing your videos.
2.  **Make it Executable** (first time only):
    ```bash
    chmod +x merge
    ```
3.  **Run Basic Merge** (Oldest to Newest):
    ```bash
    ./merge
    ```
4.  **Run with Newest First**:
    ```bash
    ./merge --last
    ```
## Parameters ⚙️
- `--last`: (Optional) Takes the very last (newest) video and places it at the beginning of the merged file. The rest of the videos follow in their original chronological order.
## Requirements 📦
- **macOS**: Built and tested on macOS (Intel & Apple Silicon).
- **FFmpeg**: The script will automatically attempt to install this via Homebrew if it's missing.
---
*Created for Umer | Optimized for Speed & Simplicity 🥳*
