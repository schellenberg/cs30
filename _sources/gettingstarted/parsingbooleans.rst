Parsing Booleans
=============================

.. topic:: Quick Overview of Day

    Work together with a partner to read code and determine what it will do. Then add new functionality to the code.


Boolean Order of Operations Reminder
-------------------------------------

- NOT ``!``
- AND ``&&``
- OR ``||``


Reading Code
------------

:download:`Figure this out, without using a computer! <../handouts/explaining_booleans.pdf>`.

.. If you want, you can get an :download:`editable version of the handout <../handouts/explaining_booleans.docx>`.


*Don't open these until you have read the handout above, and figured out what will happen using only your brain!*

- `Solution to Example 1 <https://editor.p5js.org/schellenberg/sketches/36XCzEGKQ>`_ 
- `Solution to Example 2 <https://editor.p5js.org/schellenberg/sketches/X45nRNukc>`_ 


Experimenting with the Code
----------------------------

Why are all of the variables defined outside of the setup() and draw() functions? What happens if you define them inside those functions? Try it.

Talk about local and global variables, and the fact that p5js built in variables are not able to be used until the createCanvas() function is called (demo this by randomizing the x or y value of the rectangle on first run).

.. Practice Problem
.. -----------------

.. Create a sketch so that:

.. - if the mouse is pressed and the "t" key is pressed, triangles will be drawn all over the screen. Each triangle should be the same shape, just in different locations.

.. - if the "x" or "z" keys are pressed, draw ellipses all over the screen

Adding New Functionality
-------------------------

Now that you have determined how the code works, improve both of the above projects so that when the button variable is true, the rectangle can be dragged around the screen to a new location. In order to make this work reasonably well, you should drag the rectangle by middle point (half way across it vertically, half way across it horizontally). If you are unsure what I mean, take a look at the completed versions below:

- `Solution to Challenge for Example 1 <https://editor.p5js.org/schellenberg/present/k3sB-_5ag>`_ 
- `Solution to Challenge for Example 2 <https://editor.p5js.org/schellenberg/present/_xGAzqX46>`_ 

