*********@@*@**..........................................****************..
*.......**@*@@@@**.................................*******@*****.............
*.........****@@@@**...........................***@@@@*@@****......
......***********@@***......................***@@@@**@*********......
....****************@****.................************************.......
....***@@@@@@@@@@@*******..................*************@@@@@@****...*.....
...**@@@@@@@@@@@@@@@**..*.......................*****@@@@@@@@@@@@@*******...
***@@@@@@*...@@**@@@@@*..........................***@@@@@@@@@@@@@@@@@@@***. .
.**@@@@@@*....*****@@***.........................**@*...**.@@@**..*@@@@**....
......**@@@*****@@@***@@@*.......................***.....**@@@@***@****.......
.......**@@@@@@@@@@@@@@@@@*.*................*.*@@@@@@@@@*@@@@@@@@*..*.........
.........*****@*@@@@@@*******...............**.@@@***@@@@@@@******.............
.............**************............ ....*******************................
...................*******.............. ....*.************....................
*....................****.............. ........*********.....................
*......................................  .........*****..Image to Ascii Art 0.6

License.
========
Cowsay cows are from the program "Cowsay", Copyright (c) 1999 Tony Monroe.
Cowsay is under the GPL (Doesn't say which version).

Most icons are from the Gnome project, which is also under the GPL (v2).

Image to Ascci Art uses the same GPL version as cowsay and Gnome 3 icons. That
would be the GPL v2.

Image to Ascii Art is (c) 2010-2013 By Enrique González Alonso-Buenaposada.

Version 0.6 notes.
==================

This started one saturday morning, when i was trying Lazarus in my netbook. 
After that I published the first version (0.0.2). Since then I've spent some
time improving the program, putting in new ideas and making it more interesting
to use. 

Compiling:
==========

Uncompress in a folder, then open the LPR file with lazarus. Then Run the 
project. 

Version 1.0.4 was used, but it should work with earlier versions of 
Lazarus.

Using Image to Ascii Art:
=========================

Linux users can compile the sources or use win32 version with wine. In fact
the program has been written using Linux, i'm just too lazy to prepare a .deb or
.rpm package properly.

The usage is quite simple, just open a image file.

To change the rendering options, just modify them. The image will be rendered
again with the new options.

There are four options available:

  I) Max width will scale the image. This control can be edited to get different 
  sizes. 

  II) X/y ratio. will adjust the height and width of the image to correct it 
  when characters are taller or wider. 

  III) The palette will choose how the image is rendered:

    Text modes:
    0	2 Shades text
    1	2 Shades text (Binary)
    2	4 Shades text
    3	10 Shades text
    4	16 Shades text
    5	70 Shades text  

    Html modes:
    6	HTML table (Color)
    7	HTML table (Shorter) --> 4096 colors only, three char per color is used.

    Html color text:
    8	HTML Color text

  IV) The inverted display checkbox changes from White over black and viceversa.
  It also changes the palette to match background and foreground. This option
  works only for plain text, html options just ignore it.

To export the text, just copy and paste it where you want. You can do this 
direcly on the text editor, or by using the copy to clipboard button. 

Text can also be saved to a file using the "Save as text" button.The save as 
text dialog allows the text to be saved as html or text. 

Also text can be saved as a bmp image using the "Save as image" button (This 
option works better with monospaced fonts).

The monospaced fonts option limits the font menu so only monsopaced fonts are
visible. The value can be changed to display all fonts.

About Cowsay.
=============
Cowsay is a program that displays a text cow speaking. It's simple, fun and
has a lot of options.

My idea, at first, was to use this program direcly. The problem with that is
that it has been written using perl and uses a lot of different files. So any
user that would like to use the cowsay button would need to install perl first
and then cowsay.

Instead I just wrote some code until it worked. It uses the cowsay .cow files, 
so all cows should be available. It doesn't work the same way exactly but the 
results are very similar. Just press the cowsay button, choose the options, 
enter a text and watch.

 ______________________________
/ Image To Ascii Art 0.6       \
\ Now with cowsay capabilities /
 ------------------------------
        \   ^__^
         \  (oo)\\_______
            (__)\\       )\\/\\
                ||----w |
                ||     ||

*Note: I have not tested all the cows with all the options. Some may work wrong,
as i haven't translated perl code, just made my own to make it work. Also I 
think there must be a lot of cows more out there to find.

Modifications and Bugfixes:
===========================

Version 0.0.2
  Version 0.0.1 Wouldn't compile in windows ¿Maybe some file was missing?
  Problems using function strToFloat in Laz Versions V> 0.9.28
  README.txt added.
  Window title changed.

Version 0.0.3
  Some minor modifications to the interface.
  Added some HTML modes.
  Added binary (0-1) mode.
  Added additional h/w ratios.

Version 0.0.4
  Added Save text file button.
  Added hints on components, now in English.
  Minor text corrections on dialogs.
  More complete palette descriptions.
  Added html color text mode.
  Added <html> </html> tags to html modes.
  Controls are now disabled while rendering.

Version 0.0.5
  Width Control edit bug solved.
  New widths added (16,48,64,80,96) 
  Y Factor control bug solved: Now it's readonly.
  Palette control bug solved: Now it's readonly.
  Now the output text displays warnings and errors.
  Enabled hints on Y factor and Palette.
  Corrected hints on main bar buttons.
  Corrected bug on save dialog.
  Separation lines are now thicker.
  Added a 'show only monospaced fonts' option.
  Save text as image added (Works fine with monospace fonts)  
  New version of the compiler used (1.04)
  Updates to the README.txt file
  Default font in memo is set to Courier New

Version 0.0.6
  Changed icons to Gnome 3.8 icons slightly modified:
    Save as text and save as image icons are now different.
  Window title now includes last file opened name.
  Images don't need to be reloaded when settings are changed.
  Fixed bug: Save as image button now gets disabled while rendering.
  Hint added to Monospaced Fonts checkbox.
  Inverted (White over black) display option.
  Copy text to clipboard button added.
  Fixed bug: 2 shades text.
  Manual modified and slightly corrected.
  Cowsay added! Still on experimental stage.

