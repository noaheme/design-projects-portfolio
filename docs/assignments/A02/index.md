# A2 – Truss Stress Analysis

## Objective
The objective for this assignment is to design and analyze a truss that can withstand a certain safety factor while staying within a group of given constraints. In doing so, this assignment will help with engineering problem solving as well as the ability to defend a decision. The defense coming from multiple tests and plenty of data. 

Constraints:

-Point B is a roller and point A is a pin.

-a=0.4m

-b=0.3m

-Force(p)= 20 to 30 kN

-The truss connected to all of the given joints

<img width="317" height="215" alt="download" src="https://github.com/user-attachments/assets/960078e3-fb06-4a44-b70a-d6485ee3215a" />

## Analyze
Truss Design:

<img width="2502" height="3236" alt="A2-1" src="https://github.com/user-attachments/assets/1a0c9463-38b5-48e0-bf0e-1c4fe63afb0a" />

The first question we were asked was to design a truss. Instantly my mind ran to what I am used to seeing in my everyday life and that quickly led me to the design that I decided on. Having the task of keeping it simple while also being able to withstand a load I knew that I had to be efficient. And there is not many options better for simplicity and efficiency than a triangle.
The triangular design would allow for a simple design of only 5 joints while maintaining a structurally sound design. To back up my decision I did some quick research and found that a simple planar truss with 3 triangles is a common design used in bridges and other everyday structures.

Calculations:

<img width="1179" height="432" alt="54919" src="https://github.com/user-attachments/assets/b5396beb-afbd-4c5f-8904-9b0963ff4a0d" />

<img width="1179" height="1285" alt="66054" src="https://github.com/user-attachments/assets/760bb1cf-6d5a-4f47-9116-06ae0cf89c15" />

<img width="1179" height="1386" alt="59624" src="https://github.com/user-attachments/assets/c0b0c081-e206-452f-9bf8-6919e5cf6941" />

The first step was creating free body diagrams of each joint which would then allow for us to solve for the internal forces acting on the truss. Starting with symbolic representation and shifting to numerical values I determined that the largest force the truss would endure would come from member CE and DE at 24.066 kN. This would come in handy when finding the cross-sectional area and estimating the weight of the truss. Generating the free body diagrams ended up being really challenging for me as I struggling with getting the angle calculations correct. But once I solved the equations symbolically I was able to plug in my values and create the table shown below.

  
<img width="1179" height="772" alt="31190" src="https://github.com/user-attachments/assets/82eaec34-f976-44c8-9a2c-137b1e30eab5" />

On first attempt. I ran into some troubles with making the truss be in equilibrium. Through some problem solving and careful observation I was able to see that I had swapped the sine and cosine values in one of my equations and was able to fix the mistake and move on. Overall I think this was a great learning opportunity as I did not take the time to go back and check my calculations when I finished, instead moving onto the next step. But the next step made me come back and fix my mistake.



<img width="1179" height="1383" alt="79367" src="https://github.com/user-attachments/assets/1951b055-ffff-4c1f-bcb8-0207b3119f16" />

Using the given values along with the 24.066 kN force determined earlier I was able to calculate the cross-sectional area of the truss by manipulating two equations to solve for the unknown value. After determining the cross-section area I used it to solve for the volume and then the mass to give me an estimated weight of the truss.

Pin Calculations:

<img width="1179" height="1482" alt="47640" src="https://github.com/user-attachments/assets/095afc8d-f050-4842-9327-36ce1aa60e9c" />

The next set of calculations I was tasked with revolved around the pins that would be holding the truss together. These calculations would prove to be tricky but came together in the end. I first listed my knowns and unknowns so I had an idea of where to work towards and what to use to get there. I then drew a free body diagram to help visualize the reaction taking place on a single pin in the truss. I knew that the end goal was to find the weight of the pins and the diameter to be used in my CAD drawing. However, I also knew that I would need my shear and cross-sectional area to be able to solve for the weight and diameter. Similarly to the cross-sectional area of the truss I was able to set two equations together and solve. I also decided on a pin length of 1 inch as it would comfortably fit into my truss. Multiplying the area and length I was able to get the volume which allowed me to get the weight. The process took some time to fully understand but was fairly straight forward as one solution helped with the next problem.

Solidworks Design:

IMAGE

For the modeling portion of this assignment I chose to use solidworks as I am trying to get more familiar with it to use on other projects. With this being said I am far more familiar with Creo so it took some getting used to before I could attack the truss. 

One I had my bearings straight I originally designed a single truss member and extruded it to its specified length. This took around 5 minutes which would have added up to take a longer time than I had hoped as well as a truss with jagged edges. I was running through my options when I stumbled on the a method used when I first started learning solidworks. I used centerlines to map out my entire design. Then using the weldment tool I was able to run AISI 1020 steel along my truss. I chose AISI 1020 as it was remotely close in density to A500 steel which was not an option on solidworks. After creating my truss I had to go into the weldment sketch and create a solid square cross-section which took some time. I then aligned all of my pin positions, cutting out the space in the mean time. This allowed me to go back through a extrude my pins through each of the 5 holes.


## Decide
_Which geometry did you select, and why? This is your first open design choice in the course — defend it._

My selected geometry revolved around a 5 pin 3 triangle design that would allow for a minimal yet affective truss. After preforming a series of calculations as well as modeling I can safely say that my truss is a valid decision for the parameters given. The truss overall was made out of fewer materials than a truss with more joints. While also supporting the load with a max force under 25kN. This load strength then allowed for pins that fit comfortably withing the truss itself. 
## Communicate

