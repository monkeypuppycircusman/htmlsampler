CHOP — here's the full breakdown:
Loading — click ↑ LOAD SAMPLE or drag any audio file anywhere onto the plugin. It auto-chops on load.
Waveform — full zoomable display. Scroll wheel to zoom, drag the zoom bar at the bottom to pan. Left-click to add slice markers, double-click a marker to delete it, switch to MOVE tool to drag existing markers. Right-click to preview from any point.
Chopping — AUTO CHOP runs transient detection (energy flux algorithm, 80ms min gap between hits), EQUAL 16 divides into 16 even slices, CLEAR wipes all markers.
16 pads — Q–P top row, A–L bottom row. Each pad plays its assigned slice with full ADSR, pitch (semitones + fine cents), gain, reverse, loop/oneshot. The active slice highlights on the waveform when selected.
Slice editor — click any pad to select it, all knobs and toggles update to that pad's settings. Reverse flips the buffer in memory per-slice. Pitch shift uses playbackRate (formant-shifting would need a ScriptProcessor — that's a next step).
Chop sequencer — 16 or 32 steps, per-pad patterns, swing knob, velocity jitter per hit. ⚄ RANDOM generates a musically weighted pattern (downbeats hit more). SPACE starts/stops.
