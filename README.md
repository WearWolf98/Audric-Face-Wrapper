# Audric-Face-Wrapper

# Skin Tone Adjustment and Face Mapping

This project processes video frames to detect a person's face, extract their skin tone, and apply it to a custom character image (`personne.png`). The result is a personalized alignment of the character image with the detected face landmarks from the video.

## Features

- Detects facial landmarks using Mediapipe.
- Extracts the average skin tone from specific regions of the detected face.
- Transfers the detected skin tone to the character image.
- Warps the character face to match the facial structure in the video frames.
- Overlays the adjusted character image onto the video frames.
- Saves the processed frames to an output folder.

## Requirements

- Python 3.7 or higher
- Mediapipe
- OpenCV
- NumPy

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/skin-tone-face-mapping.git
   cd skin-tone-face-mapping


## Getting Started

1. Locate the data file
2. Replace personne.png to a picture of a personne make sure it's png .
3. Replace scene.mp4 to the video file you want
4. Run the program and wait
5. Have fun.
