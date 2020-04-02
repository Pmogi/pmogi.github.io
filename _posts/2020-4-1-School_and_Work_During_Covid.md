---
layout: post
title: School and Work during COVID-19 + Tkinter GUI
---

Class work has changed a bit after the COVID-19 outbreak, all the classes have gone online and all communication for capstone project is done online. The capstone class was already sort of a mess in my opinion from the last two quarters, so this is just the icing on the cake. The real feature of the week was a 'Zoom meeting raid', where some kids raided the music GE class I'm taking and spewed obscenities at the professor. Really goes to show how unprepared the Zoom platform is for this scale of usage. Also, honestly, I never heard of Zoom until a couple months ago, so I'm surprised to see how prevalent it is.

Yesterday, for the quarantine, I moved back home and reorganized my room. I think reorganizing the room, and making a work-orientated space, will help me get into a different mindset than 'home = break time'. Although, coming back home means I've also got a lot of extra furniture from when I was living at my house in Santa Cruz. I've got my futon bed just kinda flopping around my room and I've got to figure out what to do with it. Having it be like a pseudo-couch in my room is the best idea I've got, but it's so floppy. :V

This weeks project for the capstone project will be properly piecing together the GUI for controlling my team's device in an actual structure. Currently, it's a couple widgets strung together loosely, which works for the application of a 'proof-of-concept'. Outside of the proof-of-concept realm, when adding additional widgets, is awkward. So, sitting down, reading the Tkinter documentation thoroughly, and making a class that's easily extendible will make the rest of the GUI program painless. It's just awkward how a lot of the examples for Tkinter cycle between object-orientated class and method examples and scripting. However, I shouldn't have to rely on random examples on the web!

I've also learned that threads and GUI's go together like peanut-butter and jelly. The usefulness of daemon threads for handling changes from the user and the serial communication is not be understated. After I restructure the GUI module to be more easily extendible, I'm going to use a thread to check the status of the connection between the MCU and PC and report that change to the user on the interface. I think this will be a useful addition to the PC application, and help solidify the work flow for updating the interface with text. Plus, it'll solve the IT issue of 'did you plug it in?'

Written while listening to Cowboys from Hell by Pantera. Pretty cool metal album, been revisiting some classic thrash metal today.
