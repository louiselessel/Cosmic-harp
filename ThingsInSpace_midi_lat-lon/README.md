Things in Space
===============
Revised code by Louise Lessel.
Takes a latitude and longtitude on earth, and a diameter in kilometers,
and views into space to find the satellites that are above you right now.

Forked from ajmas (https://github.com/ajmas/ThingsInSpace)
Original author: James Yoder (https://github.com/jeyoder)
A real-time interactive WebGL visualisation of objects in Earth orbit
The official live version is hosted at http://stuffin.space/

Installation
------------

For the most part it is simply a question of dropping
the files into a folder and serving them up from there.

If any changes are made to the underlying javascript 
files, then the script-loader.php will need to be run, as follows:

    php script-loader.php > scripts/script-loader.js
    
This step is done to avoid needing an environment that provides php on the public facing server. For example, 
this allows the project to hosted on `github.io`.

Getting TLE data
----------------

While TLE data (Two-Line Elements) is included in the project, it won't be up to date.

If you wish to get current TLE data, then head over to [Space Track](https://www.space-track.org/), 
login and then you can use the following URL:

https://www.space-track.org/basicspacedata/query/class/tle_latest/ORDINAL/1/EPOCH/%3Enow-30/orderby/NORAD_CAT_ID/format/json

Paste the newwest data into the TLS.json file, inside the data folder.


Starting up the installation
----------------

1. In terminal:
    cd path../ThingsInSpace_midi_lat-lon
    python -m http.server 8000

2. In Google Chrome:
    http://localhost:8000
    
3. Open Max file for data handling from webmidi (passes this on to Ableton)

4. Open Ableton file for sound (the data drives a distortion on the sound)
