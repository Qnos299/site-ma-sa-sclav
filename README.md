# Elegant Media Display

## Overview
This project is a simple HTML and CSS-based webpage that dynamically displays an elegant media layout featuring an auto-scrolling photo background and a centered video.

## Features
- **Dynamic Background**: Multiple rows of images that scroll infinitely.
- **Auto-reset Animation**: The background rows reset every 2 seconds.
- **Centered Content**: A video and an image displayed at the center with a blurred backdrop.
- **Autoplay Video**: The video plays automatically, loops, and has no controls.
- **Scrollbar in Content**: Allows scrolling for overflow content.

## File Structure
```
/ Elegant Media Display
|-- index.html
|-- /photos/
    |-- photo1.jpg
    |-- photo2.jpg
    |-- ...
    |-- photo17.jpg
    |-- bottom-image.jpg
|-- CACA.mov
```

## How to Use
1. Place all your images (JPG format, named `photo1.jpg` to `photo17.jpg`) inside the `/photos/` directory.
2. Ensure the video file `CACA.mov` is available in the root directory.
3. Open `index.html` in a browser to view the site.

## Customization
- **Change Background Speed**: Modify the `animation-duration` in `.background-row` inside the CSS.
- **Adjust Reset Timing**: Modify `setInterval(resetRows, 2000);` in the script section to change the reset interval.
- **Add More Images**: Update the script to include more images if needed.

## Requirements
- A modern web browser (Chrome, Firefox, Edge, etc.)
- Local or remote hosting for video autoplay support

## License
This project is open-source and free to use and modify.

