
# File Organizer

This Python script organizes files from a specified source directory into destination directories based on file types. It uses the Watchdog library to monitor changes in the source directory and categorizes files into different folders.

## Features

- **Dynamic Source and Destination Directories:** Choose the source directory to monitor and set up destination directories for different file types.
- **Real-time Organization:** Files are organized automatically as they are added or modified in the source directory.
- **Customizable File Types:** Easily customize the file types for audio, video, image, documents, PDFs, and executables.

## Usage

1. Modify the `source_dir` and destination directories (`dest_dir_music`, `dest_dir_video`, etc.) based on your preferences.
2. Run the script (`file_organizer.py`) in a Python environment.
3. The script will organize files into the specified destination directories based on their types.

## Destination Directories

- **Audio:** Destination for audio files.
- **Video:** Destination for video files.
- **Images:** Destination for image files.
- **Documents:** Destination for general document files.
- **PDFs:** Destination for PDF files.
- **Docs:** Destination for document files.
- **Exe:** Destination for executable files.

## Requirements

- Python 3.x
- Watchdog library (`pip install watchdog`)

## Example

```bash
python file_organizer.py
```
