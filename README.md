# Cosmic-harp

How much trash is passing by right now, over your head, unnoticed?
Playing the Cosmic Harp you’ll be able to hear what is otherwise invisible. The laser strings, which are only noticeable when interrupted by hands or smoke, create the perfect metaphor for the invisible problem of human pollution, which already extends beyond earth and into space.

As of June 2019, there are 19,685 satellites in orbit in space, 12,297 of which are classified as debris. Making the universe above us consist of 62.5% space trash.

The harp is designed with inspiration from the Armillary sphere, used in astrology in the 16th century to keep track of the heavenly bodies.
A modern update to this concept, the harp takes the section of the universe located above its current location on earth’s surface, and generates sound. The sound is updated every 15 seconds with changes, based on a satellite position dataset from space-track.org. The sound distorts and twists proportionally to the ratio of debris/ active-satellite passing by overhead.

Space-track.org is managed by the U.S. Strategic Command to provide Space Situational Awareness (SSA) information.


Code from Things in Space, to fetch satellite data
----------------
Revised code by Louise Lessel.
Takes a latitude and longtitude on earth, and a diameter in kilometers,
and views into space to find the satellites that are above you right now.

Forked from ajmas (https://github.com/ajmas/ThingsInSpace)
Original author: James Yoder (https://github.com/jeyoder)
A real-time interactive WebGL visualisation of objects in Earth orbit
The official live version is hosted at http://stuffin.space/

See additional information in README.md in the thingsinspace folder.


Starting up the installation
----------------

1. In terminal:
```console
    cd path../ThingsInSpace_midi_lat-lon
    python -m http.server 8000
```

2. In Google Chrome:
    http://localhost:8000
    
3. Open Max file for data handling from webmidi (passes this on to Ableton)

4. Open Ableton file for sound (the data drives a distortion on the sound)
You can now play sound where the distortion is driven by the amount of space trash (satellite debris) passing by above in realtime.

You can play the sound without the harp. Just hit your keyboard.

Sound created in Ableton Live Lite 9.
