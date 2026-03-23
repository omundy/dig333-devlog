[<](README.md)

# DevLog 06




## Outcomes 

<!-- 
Using the backslash preserves the list number 
https://stackoverflow.com/a/50916345/441878 
-->




omundy/learn-computing/command-line 


1\. Follow the [Command Line tutorial](https://omundy.github.io/learn-computing/slides/command-line.html). Watch [
Basic Terminal Usage](https://www.youtube.com/watch?v=jDINUSK7rXE). Describe in your own words what each of the following commands will do ✏️ 

```python
cd ~/
mkdir test && cd test
touch hello.py
echo "print(Hello World)" > hello.py
python hello.py
```

- 'cd ~/' Go to the current directory and stay in it.
- 'mkdir test && cd test' Create the directors test and go to that directory.
- 'touch hello.py' Create the file hello.py.
- 'echo "print(Hello World)" > hello.py' This prints out the thext inside the quotes to the terminal and redirects that output into a file. As in it creates a file and writes that text into it.
- 'python hello.py' Open the python file hello.py with python interpreters.


2\. Share 3 differences between the Raspberry Pi and Raspberry Pi Pico ✏️

1. The Raspberry Pi can handle more compute power than the Pico with its 1.4GHz quad-core 64-bit ARM processor
2. The Raspberry Pi can take usb input
3. The Raspberry Pi uses linux and has a main operating system and can supprot videeo display where as the pico is a microcontroller.


3\. Why shouldn't you power your Raspberry Pi from your computer USB? ✏️

- My computer only provides 500mA which is insufficient to power up the Pi, and with the insufficient current and voltage, damages may occur.


4\. Of the ways to destroy a Raspberry Pi, which are you most likely to do? How will you keep from doing it? ✏️

- Probably connecting more than 3.3V to the pins. I have put a note on my work tray and in stickies.


5\. Raspberry Pi OS is based on what Linux distribution? What does that even mean? ✏️

- The Pi OS is based on Debian which runs on the linux kernel


6\. What does it mean to "Flash" your SD Card? ✏️

- This is writing an OS image onto the SD card.


7\. What does it mean if you see a red light and a flashing green light on your powered Raspberry Pi? ✏️

- The red light means the Pi is receiving power and the green light if it is flashing means there could be an error given the error pattern. 


8\. What does a package manager do? ✏️

- This is the tool that handles software installation and updates and removals.


9\. Describe how you might use Git with a Raspberry Pi? ✏️

- Git could be used to manage versions of softwares. 


10\. What are two things your personal computer and a linux OS like Raspberry Pi have in common?

1. They both have a terminal 
2. They both have a GUI







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
