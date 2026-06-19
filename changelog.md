v0.1.0:
- Initial FlipMIDI release.
- Added `.mid` file picker rooted at `/ext/apps_data/flipmidi/songs`.
- Added Standard MIDI format 0 and format 1 parsing, with best-effort format 2 playback.
- Added PPQ timing, basic SMPTE timing, tempo changes, running status, note on/off, velocity-zero note-off, and program changes.
- Added monophonic buzzer playback with smart note selection, simple instrument styles, pause/resume, and master volume controls.
- Added host parser tests and a tiny example MIDI fixture.
