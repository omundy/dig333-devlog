
# dig333-devlog

#### Weeks: [1](#week-1) [2](#week-2) [3](#week-3) [4](#week-4) [5](#week-5) [6](#week-6) [7](#week-7) [8](#week-8) [9](#week-9) [10](#week-10) [11](#week-11) [12](#week-12) [13](#week-13) [14](#week-14) [15](#week-15)










<!--
BELOW IS A WEEKLY TEMPLATE. COPY/PASTE IT TO ADD A WEEK. SEE ASSIGNMENTS FOR DETAILS 
https://docs.google.com/document/d/1PAoPz-3vDPFWS5q9RHRb-dC7T4earpFXJW8w6v9wfZ0/edit
-->



## Week 1

### Context
  
- The TEDx presentation by Tom Igoe discusses how physical computing is the concept of computers tracking physical inputs from people.  He gives multiple examples such as a flight simulator where someone actually flaps his arms like wings and one where a tub of mud is used for input.  He also discusses the pros and cons of the open source physical computing community.
- "I wanna see a place where there is flow between these two different models." - Tom Igoe
    - Tom is referring to the model of big manufacturing and the model of open source schematic sharing.
- It is definitely encouraging to see communities being open to newcomers and everyone helping each other develop their skills and products.
- Where should the line be drawn for what kind of schematics should be open source?

## Week 2

### Context

- The article "The Internet of Things: Roadmap to a Connected World" by Sanjay Sarma discusses how quickly the number of interconnected devices across the world has grown.  Sanjay believes that in order to have better structure for all these devices there must be an "agreement on system architecture", "development on open standards reflecting the best architectural choices", and the "creation of a 'test bed'".  The article "The Internet of Things has a dirty little secret: it's not really yours" by Internet of Shit discusses the grim modern reality of how every device is becoming a "smart" device that is connected to the internet.  Despite being supposedly "smart", these devices are usually less reliable and last for a shorter amount of time than their "dumb" counterparts.
- "What we really need from those building the Internet of Things is commitment." -Internet of Shit
- Both authors clearly have concerns with the current state of the Internet of Things, but they also are optimistic for the future.
- At what point will consumers begin to draw the line for what products they want connected to the internet?

### Experiments

<!-- List each Platt experiment / Monk recipe outcome, adding notes, photos, schematics, captions to show your work. -->

#### Platt Chapter 1

1. Taste the Power!
    1. ![Tasting the power](./taste_the_power.jpg)
    1. Lower resistance means a higher current
    1. Why does the current increase when the probes are farther apart.
1. Let's Abuse a Battery!
    1. Notes
        1. Flow of electricity per second is measured in amperes
        1. Pressure of electricity that causes the flow is measured in volts
        1. Resistance to flow is measured in ohms
        1. A higher resistance restricts current
        1. A higher voltage is better able to overcome resistance
        1. Current from a battery is DC 
            1. DC current flows in one direction
        1. Current from wall outlets is AC current
            1. AC current has a pulsing flow
    1. The relationship of voltage, resistance, and current
    1. Why did we not feel any heat on our tongue in the first experiment?
1. Your First Circuit
    1. Notes
        1. Resistors
            1. First two stripes are the digits
            1. Third stripe is what order of magnitude
            1. Fourth strip is tolerance, or accuracy
        1. LEDs
            1. forward voltage is the max voltage an LED can receive
            1. forward current is the max current that can pass through an LED
        1. ![My First Circuit](./experiment3.jpg)
    1. Learned the basics of setting up a circuit
    1. How could we make the LED brighter with only changing one thing?
1. Variable Resistance
    1. Notes
        1. A potentiometer works by having a wiper rub against a resistant material as it is turned
        1. Using one instead of a static resistor provides variable resistance which enables us to dim and brighten our LED 
        1. Potential difference is the voltage between two points
        1. ![Circuit with variable resistance](./variableRes.jpg)
        1. Ohm's Law: v = I x R
        1. Resistor's in series double resistance while resistors in parallel halve it
        1. watts = volts x amps   

#### Monk Chapter 1

1. Selecting a Model
    - model 4 is good for desktop replacement
    - model 3B+ is good for general use
    - models 3B, 2B, 3A+, Zero and Zero W are smaller, but don't have wifi
1. 
3. Enclosing a Raspberry Pi
    - enclosing is important to protect it from short circuiting
4. Selecting a Power Supply
    - 1A minimum
5. Selecting an Operating System
    - different operating systems for different use cases
1. 
1. Installing an Operating System With NOOBS
    - avoid preinstalled images in order to get all the benefits of raspberry pi os
1. 
1. 
1. 
1. 
1. Using a Composite Video Monitor/TV
    - HDMI and composite video outputs
        - HDMI is better quality
1. 
1. Maximizing Performance
    - overclocking makes it faster, but also consumes more power and run hotter
1. 
1. Shutting Down Your Raspberry Pi
    - pulling the plug can cause file corruption unlike shutting down
 


## Week 3

### Context

- The "Critical Engineering Manifesto" is exactly as it sounds, a list of rules for all critical engineers to follow.  Rule number 4 seems the most interesting since it pushes engineers to think of the ethical implications of their work.  The "Artist Profile: Julian Oliver" gives an in depth interview of one of the writers of the manifesto.  He has made some interesting projects including a Transparency Grenade, which looks like a Grenade, but instead of an explosion it hacks into nearby systems and leaks the data.  "All Watched Over By Machines of Loving Grace" documents how the philosophy of Ayn Rand affected the economy in America.  Randians believed that with the aid of computer technology, people could be truly free.
- "We think through tools both before and while we use them and the more we depend upon a tool the more we are changed by it." - Julian Oliver
- I find it really interesting how economists and politicians believed in the power of computers to stabilize the economy in a way that borders on almost religious faith.
- How do we form better practices to create with ethics in mind?


### Experiments

<!-- List each Platt experiment / Monk recipe outcome, adding notes, photos, schematics, captions to show your work. -->

#### Monk Chapter 2
1. Connecting to a Wired Network
    - ssh pi@bradypi
2. Finding Your IP Address
    - hostname -I
    -ipconfig
3. 
4. Setting the Network Name of a Raspberry Pi
    - configuration tool
        - menu -> preferences -> Raspberry Pi Configuration
    - command line
        - sudo raspi-config
         - Network Options
5. Setting Up a Wireless Connection
    - from Desktop
    - command line
        - sudo raspi-config
             - Network Options -> WiFi
6. Connecting With A Console Lead
    - Menu -> Preferences -> Raspberry Pi Configuration -> Interfaces
        - click enabled button for Serial Port
    - sudo raspi-config
        - Interfacing Options -> Serial
    - need to install Putty for Windows
7. Controlling the Pi Remotely with SSH
    - ssh pi@<strong>you_pi_name_here</strong>
    - ls
        - list all sub directories and files
    - cd
        - move to next or previous directory
    - code
        - open directory in visual studio code
## Week 4

### Context
- Philip K. Dick's *Pay For The Printer* takes place in the post-apocalypse where an alien species that is able to copy objects tries to save humanity.  *The Preserving Machine* by the same author is about an invention that turns music sheets into living creatures.  Of course this goes horribly wrong when the creatures begin to evolve.  The second part of Adam Curtis' documentary *All Watched Over by Machines of Loving Grace* documents the height of the theory of balance in ecology as well as cybernetics.
- "Cybernetics sees human beings not as individuals, but as components in a system"
- All three of the material from this week's context reminds me of black boxes.  Especially the Philip K. Dick stories.
- When does using black boxes become problematic?

### Experiments

#### Monk Chapter 3

1. Browsing Files Graphically
    - Typical graphical file system interface 
2. Copying Files onto a USB Flash Drive
    - drag files into USB folder or cp in command line
3. Starting a Terminal Session
    - can open from desktop
4. Navigating the Filesystem Using a Terminal
    - prompt: command to give a parameter
    - path: file path between directories
    - root: the root directory
    - home: the default directory of the terminal
    - ~: representation of home directory
    - cd: navigate
    - ls: list all files and folders in current directory
    - pwd: show path from home to current directory
5. Copying a File or Folder
    - cntrl+c or cp in terminal
6. Renaming a File or Folder
    - ```mv my_file.txt my_file.rtf```
7. Editing a File
    - ```nano my_file```
    - <em>Ctrl-X</em> : exit
    - <em>Ctrl-Y</em> : next page
    - <em>Ctrl-W</em> : previous page
    - <em>Ctrl-O</em>: write
8. Viewing the Contents of a File
    - ```cat```
        - whole file
    - ```more```
        - one page at a time
9. Creating a File Without Using an Editor
    - ```echo "contents here" > test.txt```
10. Creating a Directory
    - ```mkdir mydirectory```
11. Deleting a File or Directory
    - ```rm my_file.txt```
    - ```rm -r my_directory```
12. Performing Tasks with Superuser Privleges
    - ```sudo reboot```
13. Understanding File Permissions
    - ```ls -l```
    - read, write, executable
    - Permissions Block
        - Type
        - Owner
        - Group
        - Other
14. Changing File Permissions
    - ```chmod u+x file2.txt```
    - need to edit or execute a file you currently don't have permission for
15. 
16. Making a Screen Capture
    - ```scrot -d 5```
    - ```scrot -s```
17. Installing Software with apt-get
    - ```sudo apt-get install <name of software>```
18. Removing Installed Software with apt-get
    - ```sudo apt-get remove <software>```
    - ```sduo apt-get autoremove <software>```
    - ```sudo apt-get clean```
19. Installing Python Packages with Pip
    - ```sudo pip install svgwrite```
20. Fetching Files from the Command Line
    - ```wget url_here```
21. Fetching Source Code with Git
    - ```git clone repository_url```
    - ```python file.py```
    - ```git remote add origin url_here```
    - ```git add .```
    - ```git commit -m "my commit"```
    - ```git push origin main```
22. Fetching This Book's Accompanying Code
    - ```git clone book_github_url```
    - ```unzip file.zip -d destination_folder```

    
