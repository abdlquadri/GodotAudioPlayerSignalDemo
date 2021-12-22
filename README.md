# GodotAudioPlayerSignalDemo

Godot master branch emits `finish` signal inconsistenty for different audio files.

Audios `001001.mp3`, `001001.ogg` does not emit `finish` while `002030.mp3` does emit.

Godot 3.4 behaves correctly. Meaning all files emit `finish` signal.