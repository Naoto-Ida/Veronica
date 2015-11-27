# Veronica
Voice control your home

## Notice
I am currently looking for a buddy to build this in Python with me. Please contact me if you are interested. I have some code to share with you.

## General
Veronica is a voice automation suite for your home.
It is an open-source project influenced by [Jasper](https://github.com/jasperproject/jasper-client), 
but with more emphasis on interacting with devices and sensors, and making it easier for the average Joe to start.
It runs off of a network of Raspberry Pi with microphones, and takes input from an optional smartphone with a companion app.

There will be a main server which relays the given command to the preferred client, e.g. “Turn on the TV in the kitchen” would make the main server relay the command to the client which has control over the kitchen.

Modules, which are essentially code which the clients will run, will be open to the community, and simply moving a folder in the modules directory should allow it to run it. I.e. module for controlling lights, sub module for controlling brand A’s light s, brand B’s lights, etc.

It will also monitor data regarding the A.O. thorough sensors, and users will be able to query them, e.g. “What's the average room temperature this week for the living room?”.

It will come with an installer for your Raspberry Pi running Raspbian, and in the future, an GUI installer as part of the companion app.
