# HW10
 
 Based on observation of last week's code, I wanted to control the HIGH and LOW to make the bulbs change in sequence. One millisecond equals to 1/1000 second, so 10,000 miliseconds equal to 10 seconds. I drew the diagram to pre-visualize the parellel structure. 
![image description](./1.png)  

Then, like we talked, I connected the groud to the long negative stripe. From there, I had each LED pair with one resistor and a wire that connects the + and - of power source. Here is a photo of the final setup. 
![image description](./2.png)  

When writing the code, I simply made all D ports available and make them turn on and off every 10,000 miliseconds. It forms a loop of 60 seconds. 