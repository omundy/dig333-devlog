[<](README.md)

# Week 04 - DevLog




## Outcomes 

<!-- 
Using the backslash preserves the list number 
https://stackoverflow.com/a/50916345/441878 
-->



1\. 📚Read Philip K. Dick Pay for the Printer (1956) and The Preserving Machine (1953). Write a reflection below:

- I was unable to find the books online or access them through the reading link provided in the schedule. 




2\. Connect a concept from [Synthesizing with Moog | Lesson 4: Resonance](https://www.youtube.com/watch?v=6spVzRqOsVw) to an aspect of the interface in the [Learning Synth Playground](https://learningsynths.ableton.com/en/playground) by Ableton 

- In the Moog video, I gained an understanding for the using of filters for frequency cut offs, and gained a better understanding for how useful they are with regards to sound synthesis. WHile watching the video I had an idea with regards to band pass filters and notch filters. I was wondering based of the graph that band pass filter gave, could you recreate it by using an rlc circuit (resistance, inductance, capacitive) in parallel with varying current input, and for notch filters, the same type of circuite but with the inductor and capacitor in parallel. 








3\. 📚Read Chapter 1 Get to know your  Raspberry Pi Pico (8-19) in [Get Started with MicroPython on Raspberry Pi Pico](https://www.mclibre.org/descargar/docs/revistas/hackspace-books/hackspace-get-started-with-micropython-on-pico-01-202101.pdf). Read and follow tutorial to install the MicroPython firmware on Pico.

p.20–25 - Read and follow tutorial to install Thonny and run the "Hello, World!" Add documentation below to show you can save and run python code on the Pico.

- I was able to run the python file on thonny using the micropython for pico w on thonny. I did this by copying the pico w 202 .uf2 file from the raspberry set up page and then installing python onto my laptop and then configuring it to run the micropython file through the interpreter. 





4\. What is the difference between a microcontroller and a regular computer? (Chapter 1)

- A microcontroller is processor designed to run specific tasks on a printed circuit board housing while a regular computer is a processor designed to run multiple concurrent tasks at the same tme. 






5\. 📚Read Chapter 2 (20–33) Programming with MicroPython. Summarize steps to program the Pico from your computer.

- Install the Thonny Python IDE
- In the interpretor section, select micropython for raspberry pi pico




6\. 📚Read Chapter 2: "Challenge: New Message" (26) - You can display programming code in a markdown file using three backticks, a new line, and then three more backticks on the following line. 

```python
print("Hello World! \nI'm Tony")
```


7\. Chapter 2: "Challenge: Loop the Loop" (26)

```python
for i in range(10):
  print("Loop number", i)
print("Loop finished!")
``` 

8\. Chapter 2: "Challenge: Add More Questions" (26)

```python
user_name = input("What is your name? ")
if (user_name != "Clark Kent"):
    print("You are not Superman - try again!")
print("You are Superman!")

user_input = eval(input("Select a random number? "))

if (user_input < 5):
    print("The given number is less than 5")
else:
    print ("The given number is greater than 5")
```






9\.  📚Read Chapter 3 (34–43) Physical Computing. How many Ground pins are on the Pico?
- There are 8 ground pins on the Pico. 



10\. Post sketches for your musical instrument and a parts list.
- I am currently still in the planning phase and plan to complete selection of my project by tomorrow night (02/16/26) and will update the devlog when this is completed













## Other experiments

<!-- 
Share details about other electronic experiments you are working on this week?
-->

- 



## Questions to bring up in class

<!-- 
Share questions you would like to bring up in class.
-->

- 
