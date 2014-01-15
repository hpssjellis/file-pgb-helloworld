file-pgb-helloworld
===================

Attempt to make an AndroidPhonegap Build file openner


JAN 15, 2014. I don't like the regular way of doing this so I am trying a jQuery style one function. Look at indexNoJquery if you want my normal way to open a file.




Got this working Jan 14, 2014.
Nicely Appends to begin with. Take out the line  writer.seek(writer.length)  and then the file is written over.

Strangely a lot of work to open and save a file. Four asynchonous events needed for each.
