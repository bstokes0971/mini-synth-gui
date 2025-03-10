# Python Mini Synth GUI

A customizable and playable synthesizer application with a graphical user interface built in Python.

<!-- <img src="./images/mini-synth-gui.png" alt="" width="500"/> -->

![](./images/mini-synth-gui.png)

## Features

- Interactive keyboard GUI that responds to clicks
- Multiple customizable sound controls
- Real-time sound synthesis
- Adjustable parameters for sound manipulation
- User-friendly interface

## Installation

1. Clone the repository:
```bash
git clone https://github.com/bstokes0971/mini-synth-gui.git
cd mini-synth-gui
```

2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows, use: venv\Scripts\activate
```

3. Install required dependencies:
```bash
pip install -r requirements.txt
```

## Usage

Run the synthesizer application:
```bash
python mini-synth-gui.ipynb
```

### Playing the Synthesizer
- Click on the virtual keyboard keys to play sounds
- Adjust the control knobs to customize the sound:
  - Volume
  - Attack/Decay
  - Pitch modulation
  - Filter cutoff
  - Resonance

## Technical Details

This synthesizer is built using:
- Python for the core application
- PyQt5 for the GUI 
- NumPy for sound wave manipulation
- PyAudio/SoundDevice for audio output

## Requirements

See `requirements.txt` for a complete list of dependencies.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.