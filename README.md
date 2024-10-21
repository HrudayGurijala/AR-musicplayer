# AR Music Application

## Project Overview
This project is an Augmented Reality (AR) music application built using A-Frame and AR.js. Users can interact with virtual instruments by scanning specific AR markers, which trigger audio playback associated with each instrument.

## Technologies Used
- **A-Frame**: A web framework for building virtual reality (VR) experiences.
- **AR.js**: A JavaScript library for augmented reality in web browsers.
- **Howler.js**: A JavaScript audio library for managing and playing sounds.

## Features
- **AR Markers**: The application uses AR markers to display images of musical instruments (drums, guitar, microphone, piano) in an augmented reality environment.
- **Audio Playback**: Each instrument has an associated audio file that plays when its marker is detected.
- **Marker Detection**: The application detects the presence of markers using a barcode type for identification.

## Assets
- **Images**: Instrument images are loaded as assets (drums, guitar, mic, piano).
- **Audio**: Each instrument has a corresponding audio file (e.g., guitar.mp3, drums.mp3).

## Getting Started
1. **Clone the Repository**: Clone this repository to your local machine.
```bash
git clone https://github.com/HrudayGurijala/AR-musicplayer
```

2. **Install Dependencies**: Ensure you have a local server set up to serve the files (e.g., using `http-server` or similar).
3. **Open in Browser**: Open `index.html` in a web browser that supports WebXR (such as Chrome or Firefox).

## How to Use
- **Scan Markers**: Use a camera-enabled device to scan the AR markers(Available in the markers folder). The corresponding instrument will appear, and its audio will start playing.
- **Audio Control**: The audio for each instrument will mute when the marker is no longer in view.

## Troubleshooting
- **Marker Not Detected**: Ensure your camera has a clear view of the marker and the lighting conditions are suitable.
- **Audio Issues**: Check if the audio files are correctly referenced and accessible in the specified directory.

## Future works 
- Can integrate a UI to guide and ask for the camera permission.
- Upload personalised songs.
## Contributing

If you'd like to contribute to this project, feel free to submit a pull request or open an issue on the GitHub repository.

## License

This project is licensed under the MIT License - see the [LICENSE] file for details.

## Contact

If you have any questions, feel free to reach out:

- **Email**: [gurijalahruday@gmail.com](mailto:gurijalahruday@gmail.com)



