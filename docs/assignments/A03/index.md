# A3 – [Topic]

## Objective

The objective of this assignment is to generate an aluminum beam in CAD using given parameters. Then taking that beam and putting it through Finite Element Analysis and analyzing the results. This process and reflection will sharpen the tools needed to complete FEA's in the future while giving us a good example of normal stress on a beam.

## Analyze

- Parametric Design:

   <img width="2502" height="3236" alt="A3-2" src="https://github.com/user-attachments/assets/a4c8e574-0df9-4817-9ad4-8faf085eeab5" />

   For part a we were tasked with setting the framework for our beam. We were given the deflection, modulus, and range for the force. I ended up choosing to go with a 400lb force as it was right in the middle of the range as well as a 1-inch diameter as it was nice and easy. I then had to find the length of the bar which involved finding the equation and solving for the length. This process was kind of challenging as it took some time but the application of the math was a fairly straight forward process. I then had to take all of my equations and numbers to solidworks to set up my parametric design and create my beam.
   After creating the beam I had to add the 400lb force pulling on the beam. I did this using the simulation tab in solidworks which I also used to run the simulation seen below. This process took some getting used to as I had never ran FEA before so the simulation tab was not even an option at the start. However, as with most things it became easier with time.

- Finite Element Analysis:

   <object data="doc2.pdf" type="application/pdf" width="100%" height="600px">
  <p>Your browser does not support inline PDFs. <a href="doc2.pdf">Click here to download the PDF</a>.</p>
</object>
   The pdf shown above shows my work in solidworks on this assignment. From the creation of the bar to the force being applied to the FEA being ran. All of it happened in solidworks. As for the simulation in particular. I was able to fix one face of the bar and apply the 400lb force to the other side. Then running the simulation to get the different stress diagrams. Through these diagrams we could see that the force was felt all through the bar however the stress was concentrated at the point of the force and slowly got weaker towards the fixed face.

   <img width="2502" height="3236" alt="A3-3" src="https://github.com/user-attachments/assets/65ed2b83-5340-4cc4-9b57-0f2784a4f769" />

   Question 2 concluded by asking for a safety check on the bar we created. It gave us 40ksi as the maximum strength of aluminum and tasked us with proving we stayed below that value. After doing the calculations I concluded that the safety factor was a whopping 78.5. While this is not a bad thing it shows that the 1 inch diameter was overkill in the creation of the bar. 
   
## Decide

- Design Reflection:

   <img width="2502" height="3236" alt="A3-4" src="https://github.com/user-attachments/assets/4e14e8c4-ba53-4bbc-8d91-5857bccfddea" />

   Using my calculated axial deflection which was equivalent to the 0.009in value given as well as the axial deflection of the FEA I was pleasantly surprised to see that my values were less than 0.3% off the value of the FEA. This was good proof that my calculations were correct. After completing both the hand calculations and the FEA I believe that I will choose the FEA axial deflection for the design as the software is less prone to accidental errors. Unlike my hand calculations where mishaps and assumptions can throw my numbers off. The solidworks software has build in code that does not round until the end which causes more precise and trustworthy answers. After determining the percent error we were asked to imagine a pin hole in the middle of the bar. I decided to make the whole 0.5inches as it simply halved the 1 inch bar diameter. After some research I found Kt and was able to determine that even with the pin the safety factor was 37.4 which is still way more than it needs to be, but still acceptable.

## Communicate

This assignment was very informative and intriguing to complete. Before this assignment I had never run an FEA or even known what it was. I was slightly familiar with solidworks but this assignment took those skills to a new level. I learned how to apply forces and fix faces to create different stresses and strains. Even with issues in finding the axial deflection in solidworks the assignment was fun overall and will definitely come in handy later on in my career. I would say this assignment took my 4-5 hours as I chose not to rush it and might have had football on in the background. Jokes aside I chose to take my time so I would actually learn the process instead of running through and forgetting everything.

## 2157 Portion: Variable Changes

For this portion of the assignment we were tasked with redoing the second part of the experiment while having changed values for force and diameter. We were also asked to guess if we thought the length of the bar would increase or decrease. For this part I decided to halve the diameter to 0.5 in as the safety factor for 1 inch seemed to be way to high while also increasing the load to 500lb to even further test the safety factor. I predict that the increase in force along will cause an increase in length but the halved diameter will significantly decrease the overall length.

<img width="590" height="256" alt="Screenshot 2026-09-09 214141" src="https://github.com/user-attachments/assets/855bb1be-2990-4d93-924c-0489c5ebf9d9" />

After running the numbers through the solidworks parameters my guess was correct. The length of the bar went down to 39.27 inches showing a major decrease from the previous length. 

[CAD File](https://drive.google.com/file/d/1dCMyVAoKjnJnPm3WtFayUxW8yR1Gy1mk/view?usp=sharing)


