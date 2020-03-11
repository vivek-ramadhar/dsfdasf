# POLIR

Raspberry Pi Camera Open-Source Laboratory Imaging Robot
Working name POLIR: Picamera Open Lab Imaging Robot

Welcome to this simple, affordable, yet powerful lab automation system inspired by open source core-xy 3D printers and the Raspberry Pi singleboard computer system.


**Developed by** 
Edwards lab, University of Reading School of Pharmacy
https://research.reading.ac.uk/biomedical-technology-lab/ 

**Why?**

Lab automation is widely used in industry, but remains too expensive for most life science researchers. Furthermore, the most effective lab automation systems are engineered for specific applications, such as high throughput screening (drug discovery, crystalisation).
Our aim was to develop open source, highly cusomisable, and extremely simple to use and develop 3-axis lab robot.

We needed this to deveop rapid inexpensive tools for detecting antimicrobial resistance (AMR).

We increasingly found optimisation of microfluidic microbiology to be slow and labour-intensive, as we require detailed kinetic information about a wide range of miniaturised microbiology experiments. Our lab was spending far too many hours manually taking digital camera photos of experiments, and we often found datasets were incomplete missing critical timepoints either due to the late hour, or rapid changes happening between observed timepoints.  
Combining RepRap mechanics and CNC software, with the fanstastic Raspberry Pi camera, was incredibly simple through use of OctoPrint software

**Capability**

* Imaging of experimental samples using x-y-z 3-axis robot
* Customisable image resolution with field of view ranging from 20 to 100mm
* Customisable size with current instrument having >300x300mm space- enough for 9x 96-well plate i.e. >>850 microtitre plate samples
* Customisable fluorescence or brightfield imaging
* Can image full experimental workspace within 3 minutes
* Fits any type of sample plate, ranging from 200 micron width microfluidic devices, through multiwell plates, to whole agar plates

**Design credits**

This project, like so many open source projects, has built upon the shoulders of the following open source giants:

3-axis robotics: 
* RepRap project, including specifically the C-bot and D-bot core-xy designs

Camera mount:
* Openflexure microscope

Electronic hardware:
* Raspberry Pi computer and camera
* Arduino 
* RAMPS 1.4 sheild (RepRap)

CNC control software: 
* Repetier firmware

Camera control and gcode supply to microcontroller:
* Octoprint



**Design details and documentation**

Full BOM, references to third party design with attributions, CAD code in OpenScad, plus guidance for use will be added to this repository.

**Example applications**

Our primary application is in analytical microbiology. We use POLIR as a tool for optimising our microfluidic microbiology technology, but it's compatible with all the standard microbiology methods.
Growth curves, metabolic profiling with different carbon/nitrogen/energy sources, motility assays, MIC and antibiotic susceptibility testing.
Traditional microbiology is laborious and scaling up experimental work to larger sample numbers requires hours of dedicated input. A major limitation is in time-resolved studies, with two options. Firstly a kinetic platereader can be used- if you have one. This will still only run a single 96-well plate. Secondly, even worse, you might have to take samples manually at many intervals, possibly all through the night.
Using the POLIR system, a wide range of experiments can be set up and simply left to record at regular timepoints during incubation. We routinely image a mixture of agar plates, 96-well microtitre plates, and microfluidic devices in parallel. Without optimisation, we can image every 3 minutes, and it will run stably for days.


**Future upgrades**
Our current POLIR systems operate in a 37 degree room, avoiding the need to install within an incubator which would likely reduce the efficiency of wireless networking. We therefore plan a custom incubator stage.
We plan to make a larger system for even higher throughput.

<img src="/POLIR_still.JPG" width="240">

![alt text](/POLIR_still.JPG)

