# Next-Sync-Player

Next-Sync is a web-based video player that supports synchronized video playback, HLS streaming, and theme toggling. Users can enter a room to watch videos together in sync across different devices. The project is built using Plyr, HLS.js, and Video Together, with DaisyUI for styling.

**Project Link**: [Next-Sync-Player](https://animegamer4422.github.io/Next-Sync-Player/)

**Note**: This project is a **WIP (Work in Progress)**, and contributions are welcome!

## Features

- **Watch Together**: Sync video playback with others in the same room.
- **HLS Support**: Stream `.m3u8` HLS video files with HLS.js.
- **Theme Toggling**: Switch between dark and light themes.
- **Responsive Design**: Works well across different devices and screen sizes.
- **Play Link Button**: Easily load video URLs with a Play button for mobile users.
  
## Technologies Used

- **HTML5**: Structure and layout.
- **JavaScript**: Core functionality and interactions.
- **Plyr**: Modern video player for customizable controls.
- **HLS.js**: Adds HLS streaming support for non-native HLS browsers.
- **Video Together**: Enables real-time video sync across devices.
- **DaisyUI**: Simplifies Tailwind CSS usage for styling.

## Setup and Usage

### 1. Clone the Repository

```bash
git clone <repository-url>
cd next-sync
```

### 2. Open the Project

You can directly open the HTML file in a web browser to test the functionality.

### 3. Key Features

#### Enter a Room
To start a synchronized playback session:
1. Open the site on multiple devices.
2. Enter the same room number on each device to sync playback.

#### Play a Video from URL
1. Paste a video URL (supports both `.mp4` and `.m3u8` formats) into the input field.
2. Click **Play Link** to start playback.

#### Upload a Video File
1. Use the **Select Video File** button to upload and play a local video file.  
   *Note: Each participant must have a copy of the same local video file to sync playback.*

#### Toggle Theme
Switch between light and dark themes by using the theme toggle switch above the video player.

## Dependencies

### External Libraries and Scripts

- **Plyr**: [Plyr.io](https://plyr.io)
- **HLS.js**: [HLS.js](https://github.com/video-dev/hls.js/)
- **Video Together**: [Video Together](https://github.com/VideoTogether/VideoTogether)
- **DaisyUI**: [DaisyUI](https://daisyui.com)

### External Scripts Used

These libraries are loaded via CDN:

```html
<script src="https://cdn.plyr.io/3.6.12/plyr.polyfilled.js"></script>
<script src="https://cdn.jsdelivr.net/npm/hls.js@latest"></script>
<script src="https://fastly.jsdelivr.net/gh/VideoTogether/VideoTogether@latest/release/extension.website.user.js"></script>
```

## Project Structure

```plaintext
├── index.html         # Main HTML file
├── styles.css         # External stylesheet
├── script.js          # Core JavaScript functionality
└── README.md          # Project documentation
```

## Future Enhancements

- Add support for custom video controls.
- Implement adaptive UI for a better experience on all devices.
- Improve room management with user authentication.
- Enhance local file sync capabilities to ensure smooth, multi-device playback.
