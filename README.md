# Pulsar Joy Waveform Visualizer

A minimalist HTML5 audio visualizer inspired by the iconic **Joy Division – Unknown Pleasures** waveform artwork and the Plexamp Pulsar Joy animation.

The visualization reacts in real time to the audio frequency/time-domain data and creates a scrolling stack of white waveform lines on a black background.

## Usage

Simply open `index.html` in a modern web browser.

1. Click **LOAD MP3**
2. Select an audio file
3. The track starts playing automatically
4. The waveform reacts to the audio

## Configuration

The main visualization parameters can be adjusted directly in the JavaScript:

```js
const CONFIG_GRAPH_WIDTH_PX = 320;
const CONFIG_VERTICAL_SPACING_PX = 8;
const CONFIG_PEAK_MAX_HEIGHT_PX = 80;
const CONFIG_LINE_THICKNESS = 1.3;
const CONFIG_PEAK_MAX_CLAMP_PCT = 1.0;

const SMOOTHING_DECAY = 0.82;
const ACCUMULATION_INTERVAL_MS = 20;
```

These control the waveform width, spacing, peak height, line thickness, smoothing and animation speed.

No build process or framework is required.

