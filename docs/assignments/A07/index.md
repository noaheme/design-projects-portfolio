# A7 – FEA on Bracket

## Objective/Overview

The goal of this assignment is to take the bracket design from A6 and FEA on the bracket. Then taking that knowledge and trying to make the bracket "better" by changing the design to be lighter, stiffer, stronger, and overall more mechanically desirable. We will repeat the process of two times to have a total of 3 different bracket designs. During each FEA we will need to note the factor of safety, stress, and displacement of the part to see if it falls withing a 7% convergence. 

For this assignment I chose to go with ASTM A36 Steel:

<img width="726" height="576" alt="Screenshot 2026-10-20 154943" src="https://github.com/user-attachments/assets/7eadfce1-a474-4c59-8e13-5e16c8de6aff" />

## Analyze

- Design 1:

The first FEA was performed on the design from A6 with no modifications made. To perform the simulation I applied a fixed geometry to the bottom of the overhang as that face will be laying on the mount. I then applied a downward force of 300N to the pin. Finally, I added a fine mesh to the entire part and ran the simulation. Below are the results.

<img width="920" height="669" alt="Screenshot 2026-10-20 161453" src="https://github.com/user-attachments/assets/92d74c56-fb7f-4ef3-91b0-9990f396bd5e" />

<img width="937" height="661" alt="Screenshot 2026-10-20 161506" src="https://github.com/user-attachments/assets/4168a61d-a7fb-4218-a4ac-26b04bad4d00" />

<img width="929" height="662" alt="Screenshot 2026-10-20 161517" src="https://github.com/user-attachments/assets/282262ca-a3fb-4ba0-9ce8-6e0f378e1416" />

From the simulation we can see the following: 

Max Stress and Location: 9.800x10^7 N/m^2 at the top intersection of the pin and the connector between the pin and the main bracket.

Max Deflection and Location: 0.2737mm at the tip of the loaded cylinder

Mass: 4.36 Pounds

Factor of Safety: 2.551

Number of Elements: 63532

Overall the design was sturdy and held a solid factor. However, it can be optimized to be lighter and even sturdier. So with that in mind I worked on my second design.

- Design 2:

Taking what I learned from the first design I moved to make a structure that was still stiff and strong yet more optimized. I did this by changing the overhand height to 1.5 inches and the wall thickness on the sides to 0.15 inches. This was in hopes to make the structure lighter while not sacrificing to much of the strength.

## Decide


## Communicate

