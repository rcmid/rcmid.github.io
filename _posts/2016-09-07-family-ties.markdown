---
published: true
title: Family Ties
layout: post
---
A family member approached me a couple of weeks ago with an interesting issue.  She had used a software program to map her family tree.  She spent considerable time and effort gathering names, dates, addresses, and other pertinent information.  She used a program titled, "Family Ties," produced and distributed by a software company named "Individual Software."  

She said she entered all of this data into the program but was having difficulty using the software on her newer computer.  She said the software would not install; none of the information on the disks was even showing up in her file manager.  I offered to help.

She brought me the disks:
<br>
<a href="http://imagizer.imageshack.us/v2/800x600q90/923/A7yIsS.jpg"><img border="0" src="http://imagizer.imageshack.us/v2/800x600q90/923/A7yIsS.jpg" /></a><br>

Oh my, those disks say, "Copyright 1994, 1995."  Huh.  As I do not have a floppy drive in any of my computers, I set about a solution.  I purchased a stand alone floppy drive with a USB interface.  Next, I copied the data from all four disks (1 data disk and 3 program disks) to my hard drive so I could work with the data without damaging the original disks.  I've encountered situations when floppy disks like these have failed (also the older 5 1/4 inch floppies) and I tried to treat them like antiques (minus wearing the white gloves when handling them). 

I copied the data file from the data disk to my hard drive.  The file type was, ".IFK" which I was not familiar with.  I assumed it was proprietary to the software company at the time.  A quick web search did not turn up any reference to the company being in business any longer.  A similar search for hints to convert the .IFK file to something useful turned up no answers. 

At the very least I wanted to see if the data file was readable (meaning not encrypted) at its most basic level.  I fired up Notepad++, with the hex editor plugin, and opened the file.  Here's the result:
<br>
 <a href="http://imagizer.imageshack.us/v2/800x600q90/922/RGgfpC.jpg"><img border="0" src="http://imagizer.imageshack.us/v2/800x600q90/922/RGgfpC.jpg" /></a><br>

Okay, it appears that in 8 bit hex view there is text that is readable, though obscured somewhat.  There's a lot more than what you can see in the picture; this is only a small snippet of the 709 KB file.  It's certainly not formatted in any way, which may prove difficult, but at least it's there.  The next step will be writing a script to parse out the meaningful data; I'll tinker with that and write another post with the results.  Wish me luck. <br>