# TapeIIMIDIITape
An experiment in recording MIDI clock and other data to "tape" (eg 48k/96k/192k digital recorders without sync capabilities) and syncing MIDI systems to "tape" playback. This project is pure hardware, with no code, but I may merge "[RetroGnome](https://github.com/crunchysteve/RetroGnome)" with it, as an included master clock system for recording...

<img width="1080" alt="Tape2MIDIv2" src="https://github.com/user-attachments/assets/41d17cb4-798a-4f3e-bb8b-d88b67065505" />

## News
30 September 2025 - have ordered 5 circuit boards for experimentation. Will report as these arrive and are tested on the bench and in the real world. Won't be testing on cassette tape as this only has a quater of the necessary bandwidth (as per Nyquist's Theorem) but the project welcomes the first person with a 32IPS reel-to-reel tape deck, who is able to bypass the audio band filters nondestructively (ie a profession-grade machine) is welcome to request a board in the mail. (Built-up or board only. Snail mail address will be required, I'm happy to post to most countries, but sadly, Australia Post is not posting to USA because of tarrif related issues right now.)

## But *WHY?!*

I have a Zoom L12 recorder and, as I slowly assemble my EDM rig and other music projects, it occurs to me that MIDI sync is the L12's only major failing. Considering this is 192kHz sampling capable recorder. Nyquist theorem predicts it should be able to easily record the 31250 baud square waves of a MIDI signal and reproduce them on playback, maybe even capable of doing so at 48kHz sample rate with a bit of pulse conditioning, but likely not for 44.1kHz.

## Again, but *WHY?!* For the love of ***GHOD!***

I love Logic Pro X for recording music but, as I look to develop my EDM skills, and having the tools I have at hand, I want to record in-sync my various and growing collection of "acid boxen," allowing for the creation of permanent song structure, while allowing for human playing differences with each performance. As the Zoom L12 is a multitake, as well as multitrack, recorder, this also allows for recording of each performance, as well as layering of performances over prerecorded accompanaments giving multiple "pattern" variations for each performance. For example, having two, parallel tracks deriving from the same synth allows for paraphonic variation via multiple synths of the same type, as well as simply performaing volume, pitch and filter changes on the box playing the recording.

In short, this can turn a high bandwidth recorder into an extremely powerful sequencer with nearly unlimited song length (other than the capacity of the SD card being recorded to), while still retaining the essentially "analog" nature of the "live jam" elements popular among EDM producers and fans.

##Roadmap

Within the next few weeks, I'll be adding a Fritzing PCB layout for the prototype, along with some pulse conditioning logic/buffering on the from-tape input line in the right-hand side of the main circuit diagram. (Right of the text, "MIDIline".)

For future plans, as mentioned above, I may merge RetroGnome into this as a MIDI master clock option. However, I want to prove the principles of the basic circuitry first.
