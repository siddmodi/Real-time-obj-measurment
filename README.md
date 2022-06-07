# Real time obj measurment

This will calculate measurment of width and height of objects using open-cv. Will open webcam and calculate width and height of an object but the object is must
be on top of an A4 sheet. We can exit the screen by pressing ESC key.

First we want to extract image of the A4 paper based on the information of height 297mm and width 210mm and based on that we'll find the objects inside the paper
and based on their pixels we define what's the size of each of the objects

We find the biggest conturs present which is the page itself in our case and warp the image of objects in [1,2,3,4] format by defining reorder function
and calculate the distance between the points which is by default the height and measurment of an object
