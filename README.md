# mu
Work in progress: Lightweight browser-based File API and Web Audio music player.

Required features:
- Web Audio + canvas visualizations
   - WaveSurfer
   - FFT for both instantaneous frequency display and time-base spectrogram
   - Live waveform
- Single playlist view (any more than that doesn't make much sense in a stateless media player; we can't [re]load files without the user's permission using the File API)
- File API -> Web Audio (i.e. whatever audio decoders the user agent supports)
  - ZIP file support
- Keyboard hotkeys
- Shuffle
- Drag-and-drop playlist order management (not critical; move [up|down] buttons work too)
- Drag-and-drop to add files to playlist
