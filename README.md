# WebAR Video Demo

This is a WebAR demo that plays videos on custom markers using A-Frame and AR.js.

## Setup Instructions

### Adding Videos
1. Place your MP4 video files in the `videos` directory:
   - `videos/video1.mp4` - First video
   - `videos/video2.mp4` - Second video

### Adding Markers
1. Create your custom markers:
   - Use a tool like [AR.js Marker Training](https://jeromeetienne.github.io/AR.js/three.js/examples/marker-training/examples/generator.html)
   - Save the marker images as:
     - `markers/marker1.png`
     - `markers/marker2.png`
   - Save the pattern files as:
     - `markers/marker1.patt`
     - `markers/marker2.patt`

### Marker Requirements
- Use high-contrast black and white patterns
- Minimum size: 5cm x 5cm when printed
- Good lighting conditions for better detection

### Testing
1. Print your markers
2. Open the deployed URL on your mobile device
3. Allow camera access
4. Point your camera at the markers to see the videos

## Development
- Built with A-Frame and AR.js
- Supports multiple markers simultaneously
- Videos autoplay when markers are detected 