# Tape2MIDI2Tape
An experiment in recording MIDI clock and other data to "tape" (eg 48k/96k/192k digital recorders without sync capabilities) and syncing MIDI systems to "tape" playback. This project is pure hardware, with no code, but I may merge "[RetroGnome](https://github.com/crunchysteve/RetroGnome)" with it, as an included master clock system for recording...

<img width="1080" alt="Tape2MIDIv2" src="https://github.com/user-attachments/assets/41d17cb4-798a-4f3e-bb8b-d88b67065505" />

## But *WHY?!*

I have a Zoom L12 recorder and, as I slowly assemble my EDM rig and other music projects, it occurs to me that MIDI sync is the L12's only major failing. Considering this is 192kHz sampling capable recorder. Nyquist theorem predicts it should be able to easily record the 31250 baud square waves of a MIDI signal and reproduce them on playback, maybe even capable of doing so at 48kHz sample rate with a bit of pulse conditioning, but likely not for 44.1kHz.

## Again, but *WHY?!* For the love of ***GHOD!***

I love Logic Pro X for recording music but, as I look to develop my EDM skills, and having the tools I have at hand, I want to record in-sync my various and growing collection of "acid boxen," allowing for the creation of permanent song structure, while allowing for human playing differences with each performance. As the Zoom L12 is a multitake, as well as multitrack, recorder, this also allows for recording of each performance, as well as layering of performances over prerecorded accompanaments.
