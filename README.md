pgb-helloworld-file
===================

Attempt to make an Android  Phonegap Build file openner


Got this working Jan 14, 2014.
Nicely Appends to begin with. Take out the line  writer.seek(writer.length)  and then the file is written over.

Strangely a lot of work to open and save a file. Four asynchonous events needed for each.
