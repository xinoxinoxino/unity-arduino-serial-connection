# Introduction #

For Mac/OSX users, I've made an implementation that uses System.Net.Sockets because the Mono implementation of System.IO.Ports is faulty on Mac.

Alas, even the System.Net.Sockets implementation doesn't work at the moment.

## Details ##

Working on Mac has brought a few problems to this project.
Although the project was meant to work on Mac, the development started on a windows PC (the project owner doesn't have a mac).

Unity is supposed to work on both mac and pc, but System.Io.Ports just doesn't work on a mac.
That's why the development continued by using System.Net.Sockets and SerialProxy to connect to the Arduino.

The .Sockets implementation was made on a PC, after completion, the project didn't work on a Mac.

This is where we are now. Getting the communication between Serialproxy and Unity up and running.
There has been communication between them, so it IS possible. But the project as it is now, does not work (on a Mac).