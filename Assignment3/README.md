# Assignment 3

Find an object and make something in 3D to add on to it with measurements (i.e. a creative lid for a cup, an add-on for your phone or DSLR camera).

1. Idea

I've been cooking a lot recently and I've had a problem with measuring things, especially liquids (soy sauce, oyster sauce, etc.). I don't have any measuring spoons so I've had to eyeball the amount listed in recipes. Thus, I wanted to make a simple tablespoon measuring cup (around 15 ml) that I can attach to my cup. 

![sketch](sketch.png)

2. Planning

To plan this project, I had to obtain a few measurements of the cup. The cup's diameter is arund 8 cm long with a thickness of 0.8cm. I decided to design my tablespoon measuring cup to be 3cm in diameter and 2.2cm in height (around 15.5ml). To account for thickness (0.2cm) I added 0.1cm for the shell. The final measurements of the cylinder were 1.6cm radius and 2.3cm height. I also made the handles 2.6cm long. Lastly, the corner sides are the same height as the cylinder height.

3. Modeling

I first started by cylinder. I then extruded it and applied the shell onto the top. The shell thickness is 0.2cm thick. 

![cylinder](cylinder.png)

I then added a plane on the top of the cylinder using offset plane then raising it by 2.3cm. I drew the rectangle that was 2.6cm by 1cm. It overlapped with the cylinder so I extruded it by -2mm and then used the join operation. 

![cylinderPlane](cylinderPlane.png)
![cylinderSide1](cylinderSide1.png)
![sideExtrude1](sideExtrude1.png)

To complete the corner, I used another offset plane on the handle. I then drew a rectangle that was 1cm x 2.3cm. I did the same process as above and extruded it inwards by 1mm and then used the join operation.

![sideExtrude2](sideExtrude2.png)
![side1Fin](cylinderSide1Fin.png)

I then just did the same thing for the other side.

![side2](side2.png)
![complete](complete.png)



