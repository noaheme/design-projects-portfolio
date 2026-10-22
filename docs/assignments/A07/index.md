# A7 – FEA on Bracket

## Objective/Overview

The goal of this assignment is to take the bracket design from A6 and FEA on the bracket. Then taking that knowledge and trying to make the bracket "better" by changing the design to be lighter, stiffer, stronger, and overall more mechanically desirable. We will repeat the process of two times to have a total of 3 different bracket designs. During each FEA we will need to note the factor of safety, stress, and displacement of the part to see if it falls withing a 7% convergence. 

For this assignment I chose to go with ASTM A36 Steel:

<img width="726" height="576" alt="Screenshot 2026-10-20 154943" src="https://github.com/user-attachments/assets/7eadfce1-a474-4c59-8e13-5e16c8de6aff" />

## Analyze

- Design 1:

The first FEA was performed on the design from A6 with no modifications made. To perform the simulation I applied a fixed geometry to the bottom of the overhang as that face will be laying on the mount. I then applied a downward force of 300N to the pin. Finally, I added a fine mesh to the entire part and ran the simulation. This was after running a course and mild mesh that had yet to converge only making it to 10%. Below are the results. 

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

Taking what I learned from the first design I moved to make a structure that was still stiff and strong yet more optimized. I did this by parametrically changing changing the overhand height to 1.5 inches and the wall thickness on the sides to 0.15 inches. This was in hopes to make the structure lighter while not sacrificing to much of the strength. I ran the FEA 3 different times going finer and finer with the mesh which did not fully converge to the 7% value but did end up somewhere around 9-10%. Below you will find the finest mesh I could run in solidworks.

<img width="903" height="575" alt="Screenshot 2026-10-21 114529" src="https://github.com/user-attachments/assets/268a56ef-649c-44b8-8ef6-ca346ed657a2" />

<img width="795" height="581" alt="Screenshot 2026-10-21 114539" src="https://github.com/user-attachments/assets/a32fcafd-04f5-45bf-b269-dc8ebc5df547" />

<img width="829" height="560" alt="Screenshot 2026-10-21 114548" src="https://github.com/user-attachments/assets/0ce89809-22e9-4c27-935b-6f2628353d09" />

From the simulation we can see the following: 

Max Stress and Location: 89.4 MPa Located at the sharp edges between the body, connector arm, and pin.

Max Deflection and Location: 0.2744 mm at the edge of the pin

Mass: 3.34 Pounds 

Factor of Safety: 2.80

Number of Elements: 49028

This design did what it was supposed to. Take material off and keep a similar factor of safety, stiffness, and strength while making it lighter. However, one thing stuck out. The factor of safety got larger. I thought there was an error so I did some research; According to COMSOL (2014) removing material can cause a reduction in the local stress levels and lead to a higher factor of safety. Knowing this, I knew I could do better. So taking what I learned I moved to design 3.

- Design 3:

Design 2 showed that removing material was not always a bad thing. But I also noticed through my first 2 designs that the stress and strain were largest at the sharp edges on the mount. I therefore joined all of the bodies to add 2 fillets to the sharp edges. I then removed a chunk of the bottom of the main body in hopes or moving more unneeded mass. Lastly I added a circle cut pattern to the main body to remove mass. This design only took 2 tests as it converged to an impressive 4.56% difference in stress and a 0.19% difference in the deflection. Below you will see the results. 

<img width="794" height="560" alt="Screenshot 2026-10-21 170156" src="https://github.com/user-attachments/assets/2a5d1617-6169-47e7-899c-c163ceac4930" />

<img width="784" height="508" alt="Screenshot 2026-10-21 170210" src="https://github.com/user-attachments/assets/c5a2f0f9-3ff1-47ec-91df-5b39f5c8eba9" />

<img width="729" height="535" alt="Screenshot 2026-10-21 170225" src="https://github.com/user-attachments/assets/96b96d9c-dcea-4be9-9b84-45ffb3798a5e" />

From the simulation we can see the following:

Max Stress and Location: 101.6 MPa located at the fillets.

Max Deflection and Location: 0.266 mm at the end of the pin.

Mass: 2.76 pounds

Factor of Safety: 2.46

Number of Elements: 364511

This design is by far my favorite. The mass dropped due to the removed material even though fillets were added. The fillets also did their job as the deflection was slightly smaller. The stress and strain increased however it is understandable as the foundation took a hit due to the holes. This also impacted the factor of safety taking it down to 2.46. Overall, I am happy with the outcome as it is lighter and stiffer while still maintaining a near 2.5 factor of safety.

## Communicate

This assignment was very informative as I learned a lot about optimization and how different changes affect the factor of safety. From the first to third design I removed almost one and half pounds while maintaining similar values of stress, strain, and FOS while making the deflection smaller. I also learned that removing material does not always lower the factor of safety. Removing unneeded materials can actually increase the factor of safety by changing the stress levels. This was eye opening and inspired me to remove more mass through cuts and holes. Overall the assignment was a great way to learn about the engineering design process while also teaching me something unexpected that will help me in the future. In total this assignment took roughly 5 hours.

## 2157 Portion: Link FEA

All using ASTM A36 Steel

- Design 1

For the link I decided to set a fixed geometry to the inside of the top hole as it would be filled with the pin. I then added a downward force of 150N to the bottom hole. I started out using a mild mesh and then used a fine mesh. The convergence was 1.2%. Below are the results

<img width="910" height="624" alt="Screenshot 2026-10-21 192404" src="https://github.com/user-attachments/assets/ff97ea88-ee81-4940-aa39-da6f7ced3f22" />

<img width="917" height="623" alt="Screenshot 2026-10-21 192418" src="https://github.com/user-attachments/assets/fb534804-81d1-4beb-932e-09bd60d46dae" />

<img width="898" height="641" alt="Screenshot 2026-10-21 192430" src="https://github.com/user-attachments/assets/84b93e58-2123-468d-8b9b-7fc55c22d2e2" />

From the simulation we can see the following:

Max Stress and Location: 5.89 MPa as the inside of the bottom hole.

Max Deflection and Location: 0.0002478mm on the bottom side of the bottom hole.

Mass: 0.39 pounds

Factor of Safety: 169

Number of Elements: 63433

The original link designed in A6 is more than strong enough to the point of a staggering 169 factor of safety meaning there was room for change to get the weight down. With that in mind I moved on to design 2. 

- Design 2

For my second iteration I decided to remove some material in the center portion of the link to save some weight as well as fillets to serve the same purpose along with aesthetic. After running it twice I was able to see that the difference was a small 3.79%. Below are the results:

<img width="911" height="583" alt="Screenshot 2026-10-21 194848" src="https://github.com/user-attachments/assets/f34397b2-4881-4bce-b3a8-b1d034338f78" />

<img width="872" height="593" alt="Screenshot 2026-10-21 194837" src="https://github.com/user-attachments/assets/aa04c4e4-8bb8-4049-b986-145214624aee" />

<img width="911" height="600" alt="Screenshot 2026-10-21 194825" src="https://github.com/user-attachments/assets/02c2ccec-45cf-417c-af64-6746f0cfc96d" />

From the simulation:

Max Stress and Location: 2.7 MPa at the center of the fillets and inside of the bottom hole.

Max Deflection and Location: 0.0004488 mm at the bottom of the link below the second hole.

Mass: 0.33 pounds

Factor of Safety: 92.5

Number of Elements: 62918

The second design took off a solid chunk of material and saw a minimal drop in mass with a large drop in the factor of safety. While the factor of safety is still large I think that it does not justify the drop in mass. The link also saw a large increase if deflection along with more points of severe stress and strain. Overall, I think the design is worse than design 1 and I took that into account with my final design.

- Design 3

My third and final design was a culmination on the information I gathered in design 1 and 2. The design reverted back to the large overall size and included holes to take out mass and distribute stress concentrations. I also went for a shell of 0.05 inches on both sides to take out some weight. The mild and fine mesh converged to a 1.4% difference and the results are below:

<img width="880" height="591" alt="Screenshot 2026-10-21 202151" src="https://github.com/user-attachments/assets/21a43872-dd16-4d76-9a18-a93bad4d25f9" />

<img width="890" height="587" alt="Screenshot 2026-10-21 202130" src="https://github.com/user-attachments/assets/38975a1a-61a2-44a7-b077-6a12b4a4f592" />

<img width="911" height="589" alt="Screenshot 2026-10-21 202107" src="https://github.com/user-attachments/assets/a7279eb0-5bdf-4cb8-94bd-d7b680786a38" />

From the simulation:

Max Stress and Location: 7.67 MPa at the inside of the holes added to "absord" stress.

Max Deflection and Location: 0.003783 mm 

Mass: 0.11 pounds

Factor of Safety: 32.6

Number of Elements: 68478

Design 3 is the most intriguing to me. And thought it might be hard to make. I think it is the best. The design has a very light weight and is so stiff that it deflects outward rather than down. At first this threw me off but I realized that it was virtually locked in the downward direction meaning it is very sturdy. The design also has a factor of safety well above the necessary amount.

## CAD Files

Note: My solidworks Simulation app does not let me save anything. It crashes my computer every time. Has all year. 

Bracket File: https://drive.google.com/file/d/1vwjdAjGjxoLyGZEpeyimlyb1xg14AshY/view?usp=sharing

Link File: https://drive.google.com/file/d/1fwjo3Q6S8e5Fa-q3QVXxZFKqd2SKiYwZ/view?usp=sharing
