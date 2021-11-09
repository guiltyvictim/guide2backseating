#Guide 2 Streaming and Editing

To ensure we have the best audio quality for editing purposes, here are some resources and general outline of our we'll record our streams moving forward.

One of the main issues we face right now is uneven loudness for each person across all streams. This is caused by a variety of issues, from differences in microphone settings to individual volume settings by whoever is hosting the streams.

In an ideal situation, we want to properly balance everyone's audio levels for each stream, but that would require a fair amount of setup. For now we'll focus on a solution that at least give us the flexibility during the video editing stage, by separating each person's voice and the gameplay in recordings.

Here are the tools we'llbe using:

- [Craigbot](https://craig.chat/home/#howtouse)
	- Craigbot can record the voice chat channel for multi-track audio. The web app can be used to record higher quality audio on top.
	- Craigbot's main advantage is that it syncs the start of all audio up for all participants, regardless of when a participant joins
- [OBS Studio](https://obsproject.com)
	- OBS Studio is needed for both compatibility (everyone on the same version) and plugins purposes
- [Win Capture Audio plugin for OBS Studio](https://github.com/bozbez/win-capture-audio)
	- This plugin allows you to capture audio sources separately in OBS, meaning you can have a separate audio source for your game and Discord, which will be important for recording clean game audio
- [Davinci Resolve](https://www.blackmagicdesign.com/products/davinciresolve/)
	- This is our full featured video editing software of choice, as it's free and allow us all to stay on the same versions and use the same tutorials and guides going forward.
- Dropbox or Google Docs
	- Manage our assets including avatars, title cards, fonts etc.

##Preparations
Recording voices in separate tracks:

1. Invite Craigbot to voice chat channel
2. Share craigbot web app url with all participants, as well as posting the download link to Storage channel (or should we have a dedicated channel for this?)
3. Each participant to setup audio source (should only need to do it once the first time)
4. Make sure craigbot web window stays open until after stream finishes or the recording will stop
5. Download the audio files
6. Save to our online repository, with proper filenames

Recording clean game audio:

- Follow [this guide](https://www.youtube.com/watch?v=c24TYzSdj-c) to setup separate audio sources for Game and Discord audio in OBS Studio
- Follow [this guide](https://www.youtube.com/watch?v=PqeRfaJuWLo) to understand how to record multiple tracks separately
	- set the game audio to track 1 & 2, discord to track 1 & 3
	- Note: Track 1 will be the mixed track, allowing the editor to reference later the timing of the voice and game audio. This is important as things like drop frames and other issues can cause video and audio to go out of sync sometimes
- Follow [this guide](https://www.youtube.com/watch?v=SyvJDtmw_Z8) to record your game audio during the stream

