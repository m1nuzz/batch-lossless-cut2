## Video Trimming Script

This batch script is designed to trim the last 3 minutes (customizable) from all video files in the folder where the script is located.

### Features
- Automatically processes all video files in the script's directory.
- Trims the specified duration from the end of each video file.
- Outputs the trimmed videos with a `_trimmed` suffix in the same directory.

### Requirements
- Ensure that the path to `ffmpeg` is added to the PATH environment variable.

### How to Use
1. Place this script in the folder containing the videos you want to trim.
2. Run the script.
3. The script will process each video file and save the trimmed version in the same folder with a `_trimmed` suffix.

### Customization
- To change the trimming duration, adjust the script accordingly.
