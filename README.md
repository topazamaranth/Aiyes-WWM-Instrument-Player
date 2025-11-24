Aiye's Instrument Player

![Screenshot](https://github.com/topazamaranth/Aiyes-WWM-Instrument-Player/blob/main/Screenshot%202025-11-23%20184911.png)

A MIDI-to-macro converter and automated playback tool for Where Winds Meet's instruments.
This is the first public release of Aiye's Instrument Player, a standalone Windows utility for converting MIDI files into playable in-game keystroke macros for Where Winds Meet.

Just open MIDI files in the program, press Play, and quickly swap to your game window — the app will perform the song using the correct keyboard mappings.

**[Click here to Download](https://github.com/topazamaranth/Aiyes-WWM-Instrument-Player/releases/download/v1.0.0/Aiye.s.Instrument.Player.exe)**


**How to Use:**

- Download and run the .exe below (no install needed) IN ADMINSTRATOR MODE.
- It MUST be run as Administrator or keystrokes will not register globally. This is a Windows limitation.
- Click Open MIDI… and add one or more .mid files.
- Select a track and press Play, or press Play Playlist.
- QUICKLY focus the game window and let the app perform the music.
- Press F11 anytime to instantly stop playback (you will need to do this).

**Limitations:**

- Songs with notes outside the 3-octave range will have lower notes culled (game limitation)
- Midis with multiple instruments, especially percussion, will sound muddy. (game limitation; piano covers usually sound good.) 

**Playlist Support:**

- Add multiple MIDI files to a playlist
- Reorder tracks using drag-and-drop
- Right-click to remove tracks
- Save or load playlists as .json files
- “Play Playlist” plays from the selected track to the end with a short delay between songs

**Automatic MIDI to Macro Conversion**

- Converts .mid files into a keystroke macro playable in-game
- Automatically transposes the song to fit the instrument’s 3-octave range (48–83)
- Rolls chords so polyphonic notes work on a monophonic instrument
- Handles tempo changes and timing accurately
- F11 global panic hotkey to immediately stop playback
- Macro generation runs in the background
- Macro caching avoids re-processing files
- Temporary files cleanly isolated in system temp folder

**Requirements:**

- Windows 
- Game window must be focused for the macro to play notes
- MIDI files should be reasonably clean (most work fine)

**Notes:**

- This tool is fan-made and not officially affiliated with Where Winds Meet.
- Use responsibly and in accordance with game rules.

**Download:**

- Scroll down and download the .exe attached to this release.
