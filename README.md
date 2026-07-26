# Mystic Arts Engine

An interactive hand-gesture animation experience built with HTML, CSS, JavaScript, and MediaPipe Hands.  
Use your camera to trigger cinematic visual effects like trails, smoke, sparks, a portal ring, and a sacred shield.

## Preview

> A futuristic, Doctor Strange–inspired gesture-based visual engine powered by webcam hand tracking.

## Features

- Real-time webcam hand tracking.
- Smooth index-finger trail effect.
- Smoke particles from open palm gestures.
- Spark bursts from fist gestures.
- Portal ring effect when both hands come close together.
- Mystic shield effect with open-hand pose.
- Hand skeleton overlay for debugging and visualization.
- Animated star-field background.
- FPS counter and effect status indicators.
- Start button to initialize camera access.

## How It Works

The application uses:
- **MediaPipe Hands** for hand landmark detection.
- **Canvas 2D** for rendering all visual effects.
- **Webcam video input** for live gesture interaction.

### Gesture Mapping

- **Index finger only** → red glowing trail.
- **Flat open palm** → smoke particles.
- **Fist** → spark explosion.
- **Two hands close together** → portal ring opens.
- **Open hand / all fingers extended** → magical shield appears.

## Project Structure

```text
index.html
```

Everything is contained in a single file:
- HTML for layout.
- CSS for styling.
- JavaScript for hand tracking and animation rendering.

## Requirements

- A modern browser with webcam support.
- Internet connection for MediaPipe CDN scripts.
- Camera permissions enabled.

## How to Run

1. Clone or download the project.
2. Open `index.html` in a browser.
3. Click **AWAKEN**.
4. Allow camera access.
5. Perform gestures in front of the camera.

## Demo Controls

- **AWAKEN** button: starts the webcam and hand tracking.
- Move your hand to generate effects.
- Use two hands for the portal.
- Make a fist for sparks.
- Hold an open palm for the shield.

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Canvas API
- MediaPipe Hands
- MediaPipe Camera Utils

## Visual Effects

### Trail
A glowing red path follows the index finger when only the index finger is extended.

### Smoke
Cyan smoke particles rise from the palm when the hand is flat and open.

### Sparks
Golden sparks burst outward when a fist gesture is detected.

### Portal
A rotating circular portal appears between two hands when they move close enough.

### Shield
A red magical geometric shield appears around an open hand.

## Notes

- Best used in a well-lit room.
- Camera quality affects hand tracking accuracy.
- The project is designed for a dramatic cinematic look.

## License

Add your preferred license here.

## Credits

- MediaPipe Hands
- Canvas API
- Inspired by mystical visual effects and cinematic hand magic
