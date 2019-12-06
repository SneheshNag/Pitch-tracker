# Pitch-Tracker

# NoteSegmentation.py
Note Segmenter python class.

## Usage
```python
from NoteSegmentation import NoteSegmenter

Ns = NoteSegmenter()

Ns.convert_freq2midi(fInHz): MIDI conversion tool #(https://www.audiocontentanalysis.org/code/helper-functions/frequency-to-midi-pitch-conversion-2/).
Ns.remove_outlier(pitch) #vibrato removal algorithm (deprecated).
Ns.segment(pitch, power) #using input pitch and power series, compute estimates for MIDI note numbers in audio.
```

# ChordPrediction.ipyndb

Jupyter Notebook containing data loading and conversion, as well as LSTM building and training.

## Usage
```bash
jupyter notebook #select ChordPrediction.ipyndb 
```