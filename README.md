# MP3 Extractor
This will be the repository for maaaybe a command line program wrapper around `youtube-dl`

Obviously, the main dependency is `youtube-dl` since I wouldn't know the first thing about extracting audio from a youtube url.
The main idea is to be able to only pass the `/watch?v=[some-code]` query string as an argument and have the program define the place where it will be downloaded.

Example line:
```
~ 🏄  :> youtube-dl --extract-audio --audio-format mp3 -l https://www.youtube.com/watch?v=8j741TUIET0
```

Maybe even pass more than one video and handle errors and shiet.

Das ist alles...
