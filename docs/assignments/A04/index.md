# A4 – Motor Mount

## Objective

The objective of this assignment is to design and create a mount for a brushed motor. In particular, making a rigid mount while maintaining a safety factor of 3. The main part of the assignment will revolve around finding the thickness of the different features revolving around given values. This will be done through calculations and visualizations with the end goal being a CAD model of the design along with a multiview drawing. This assignment will teach the ability to design around given parameters as well as incorporating a design with a real life product. 

## Analyze

Feature 1:

<img width="1081" height="1398" alt="0" src="https://github.com/user-attachments/assets/174c694d-d575-48e5-8775-d3a5857828b3" />

To start this assignment we were tasked with using and manipulating bending equations to find the thickness of the first feature of the mount. Starting with the knowns and unknowns allowed for me to see what was given or inferred and find out that in reality there was only two things to find. Those things being the thickness (h) and the stress of bending that would come from the system. After this I set up the equations given and was able to do some algebra to isolate both the thickness and the stress. I solved for the thickness using the information given as well as a 3000 modulus which was a standard middle ground for the PLA that I was using. I chose PLA as it was fairly familiar and affordable while also being able to support the motor. After solving symbolically I was simply able to plug in the numbers and find that my length should be 11.09mm which I rounded to 12mm, and that the stress on the feature was 14.6MPa.

Feature 2:

<img width="1081" height="1398" alt="0" src="https://github.com/user-attachments/assets/b2e99965-6c2d-4b31-b2a0-59bbc19d1949" />

After feature 1 it was time to create feature 2. Feature 2 was much easier as it used the same equations as feature 1, however, having to account for the extra 12mm in the base length made the math come out slightly different. Just like feature 1 I started with knowns and unknowns which allowed for me to set up the bending equations and solve for the thickness and the stress. After solving for the values needed I once again plugged in the numbers with the only difference being the extra 12mm added onto the feature to bring feature 1 and 2 together. It is also worth noting that 4 holes of 3.4mm diameter were to be placed for screws to go through. 

CAD Design:

   <object data="Doc3.pdf" type="application/pdf" width="100%" height="600px">
  <p>Your browser does not support inline PDFs. <a href="Doc3.pdf">Click here to download the PDF</a>.</p>
</object>

The CAD design was both the most enjoyable and most in depth part of the project. Starting with the original 32mmx32mm base and length moving to the different cuts so that the motor could easily sit in the mount. The assignment allowed for experimentation and allowed me to learn a lot more about solidworks. I mathematically solved for the depth so I extended the square out to make a 32mmx32mmx12mm cube. The original reason for choosing 32mmx32mm was due to the 28mm diameter cut that was to hold part of the main body of the motor. I figured that the extra 4mm was plenty to allow for a study hold while not being too outlandish. Looking at appendix a I could also see the tiny 18mm diameter by 2mm deep plate sticking off of the end of the motor right before the end. I decided to incorporate this into my design before adding the 6mm hole that would go all the way through the feature allowing for the shaft. After finishing the first feature I made another sketch onto the side face of feature 1. This 44mmx32mm sketch would become feature 2. The 44mm base length is due to the 12mm depth of feature 1 being accounted for. After again mathematically solving for the thickness of the second feature I extruded the sketch to create a 44mmx32mmx10mm block that was connected to feature 1. After adding in the 4 connection wholes at an even 8mm from each respective corner as seen in the pictures, and adding a small 5mm fillet to create a smoother looking design. I was finally finished with my motor mount.



## 2157 Section: Drawings

 <object data="A4drawing.pdf" type="application/pdf" width="100%" height="600px">
  <p>Your browser does not support inline PDFs. <a href="A4drawing.pdf">Click here to download the PDF</a>.</p>
</object>

For the 2157 portion of this assignment we were asked to take the CAD model created earlier and make a drawing of the model in solidworks. This part of the assignment while short, was one of the most challenging as I was familiar with making drawings in creo but not solidworks. Once I was able to figure out the annotations I place down the different views and was able to create a solid representation of my part in a drawing. 


## Communicate

This assignment was very challenging but also very informative as it taught me multiple things about the design process and solidworks itself. The assignment was tough as I had issue with solidworks itself along with small miscalculations in the math that required me to go back and recalculate. But overall the assignment was very informative as it allowed for my own creations to be mixed with a set of given parameters to eventually get an outcome. This assignment from start to finish took me roughly 7 hours however the first few hours were spend understanding the question and the end goal that were asked of me.



