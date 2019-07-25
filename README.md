# 00-course-overview

Course overview, syllabus, schedule, etc. for the Beaver Works Summer Insitute (BWSI) summer remote sensing course

## Introduction

The Beaver Works Summer Institute will offer students the opportunity to explore the exciting intersection of data science and crisis response. During the course, the students will learn the basics of Python, Git, geospatial information systems (GIS), and image processing. Students will explore real world datasets including aerial imagery from drones and Civil Air Patrol, as well as various satellite sources. Students will develop experience in an area of data science that is poised to play a critical role in understanding our world.

## Program Overview

Imagine coordinating a response after the chaos of a hurricane or the challenges of a famine lasting years; these big problems require big data to solve. With airplanes and satellites, we collect mountains of data of affected regions, but who looks at this data? How do we turn this data into a physical response? The program’s goal is for participants to explore, leverage, and transform open source information and imagery collected from drones, airplanes, helicopters, and satellites to generate actionable intelligence to support a disaster or humanitarian response. Students will be exposed to three main components: 1) processing and extracting features from raw data, 2) data classification and analysis, and 3) developing data products to support decision making. The program will explore tools and techniques using real world operational data collected from across the globe.

The BWSI Remote Sensing program offers high school students the opportunity to explore the exciting intersection of data science and crisis response.  The program consists of two components: (1) online course from January to May, open to all interested and committed students; and (2) a four-week summer program at MIT campus in Cambridge, MA. During the course, the students will learn to understand the basics of Python, Git, machine learning, and image processing. Students will explore real world datasets of aerial and satellite imagery. By participating in the online and/or onsite portion of the program, students will develop experience in an area of data science that is poised to play a critical role in understanding our world.

## Online Course

Prior to the summer course at MIT campus, students will be required to complete an online course which contains important introductory material. The online course will give the students a strong foundation required to successfully complete the four-week summer course. In addition to foundational introductory material, the online course includes discussion of different use cases and expose students to real world challenges and applications of the coursework.

## Summer Syllabus - Weekly

The four-week summer component of aims to guide students through the processing of designing experiments and analyzing commonly used for data for disaster response.  Daily course material, case studies, guest lectures, and small-group projects will expose students to challenges across technical domains. This syallabus is subject to change over the duration of the course.  

### Week 1: Foundation

1. Introduction to Remote Sensing for Humanitarian Assistance and Disaster Relief
2. Review of online Python course
3. GIS and networks in Python
4. Field trip to MIT Lincoln Laboratory

### Week 2: Data Science and Analysis

1. Introduction to engineering design and data science principles
2. Images, metadata, and image processing
3. Field trip to Massachusetts Task Force One (MA-TF1)

### Week 3: Aerial Imagery and Sensing

1. Civil Air Patrol and Aerial Imagery
2. Internet of things and analyzing aerial images
3. Building a hardware multispectral sensor
4. Kite photography
5. Field trip to Draper Laboratory

### Week 4: Optimization Decision Making

1. Network optimization and class optimization formulations
2. Guest lectures from Swissnex and Red Cross Red Crescent Climate Centre
3. Final exercise of disaster tabletop simulation

## Summer Syllabus - Learning Objectives

### First Day

1. What is this course about? Who is everybody?
2. What is Remote Sensing?
3. Why do we need to sense things?
4. What is HADR? Who provides HADR?
5. What is Emergency Management
   1. The roles of various agencies/levels
   2. Tasks required of agencies
   3. Core concepts
   4. Scenario-based planning
   5. What information is needed to plan and respond?
6. Team Building: Everyone writes an interesting fact about them on a piece of paper and puts it in a bucket. Everyone draws a piece of paper from the bucket and tries to find the person associated with that fact
7. Brainstorm: Sensing modalities
   1. Identify quantities that may be useful for sensing in emergency situations
   2. How could you sense those quantities? e.g. visual, particulate, temperature, conductivity
   3. What limitations do you have? e.g. power/comms requirement, occlusion, calibration, noise, resolution, observability
   4. What are the costs?
   5. Community/crowdsourcing – how to task people to help with sensing? What considerations do you need to take into account? Safety, accuracy, trustworthiness, bias

### Python

[00-InitialSetup](https://github.com/bwsi-hadr/00-InitialSetup)  
[01-Intro-to-python](https://github.com/bwsi-hadr/01-Intro-to-python)
[02-visualization-and-shapes](https://github.com/bwsi-hadr/02-visualization-and-shapes)

1. How to use Jupyter/Colab Notebooks
2. Install system packages with apt, and python packages with pip
3. Fundamentals of python and programming:
   1. packages
   2. loops and conditionals
   3. functions
   4. data structures: lists, dictionaries, iterators
4. Numpy
   1. Arrays
   2. Indexing
   3. Matrix math
   4. summary functions (max, min, std, avg)
5. Pandas
   1. column names, data types
   2. filtering and logical indexing
   3. joining, pivoting
   4. generating statistics
6. Visualizing data
   1. matplotlib, histograms, heatmaps, imshow
   1. time series, graphs

### GIS and Networks

[03-Intro-to-GIS](https://github.com/bwsi-hadr/03-Intro-to-GIS)  
[04-Intro-to-networks](https://github.com/bwsi-hadr/04-Intro-to-networks)  
[05-Intro-to-Data-Science](https://github.com/bwsi-hadr/05-Intro-to-Data-Science)

1. Engineering design and data science
   1. How is data used to make decisions?
   2. How to identify requirements, constraints, and problems?
   3. How to effectively communicate between teams?
   4. How can engineering projects fail? What causes failures? How do we learn from failures?
   5. How to store and access data in a database for analysis?
2. Geographic information system (GIS)
   1. How to use GeoPandas
   2. How to load various GIS file formats
   3. How to load raster files with GDAL
   4. How to create a map with layers
   5. How to do spatial calculations
3. Common GIS tasks
   1. Loading basemaps from repositories
   2. Loading shapefiles of data layers
   3. Geometric operations for overlays, intersection, union, etc
   4. Reclassifying data
   5. Loading raster files
   6. Computing nearest neighbors, distances, spatial averages, spatial join
   7. Machine Learning and forecast-based financing
4. Networks
   1. What are networks and how to use them
   2. How to get network data from Open Street Maps?
   3. What math can be done on networks, how do these algorithms work?
   4. How to visualize networks in GIS?
   5. Network properties: edges, vertices, adjacency, matrix representations
   6. Shortest path, Djikstra&#39;s algorithm, shortest path tree, minimum spanning tree, centrality
   7. Plotting measurements on the network
   8. Converting graph to geodataframe
   9. Exporting to raster, shapefile

### Aerial Photography and Image Processing

[06-Intro-to-Image-processing](https://github.com/bwsi-hadr/06-Intro-to-Image-processing)  
[07-Satellite_Image_Processing_Using_Python](https://github.com/bwsi-hadr/07-Satellite_Image_Processing_Using_Python)

1. What is the Civil Air Patrol (CAP)?
   1. History and mission of CAP
   2. What information does aerial imagery provide?
   3. What challenges are there in dealing with aerial imagery?
   4. What goes into planning CAP missions? Elevation, distance, path, targets
2. What kind of information is available from satellite imagery, and how is it used?
   1. Sources of public imagery
   2. Sensing bands
   3. Preprocessing, Calibration
   4. Analyses, uses, limitation
3. Imagery data
   1. How are images represented on a computer?
   2. What are pixels, channels? What do they represent?
   3. What is metadata? EXIF?
   4. Understanding color systems and decomposing images into channels: RGB, HSV
   5. Understanding convolution kernal filters
   6. Accounting for heading, orientation, distortion of aerial images
   7. Stitching together images
4. Databases to store data
   1. Why do we need databases?
   2. SQL and noSQL databases
   3. Queries, Inserts, Joins, Updates
   4. Setting up a web server
5. Internet of Things (IoT)
   1. What are web apps, how are they structured?
   2. Scraping data from websites (Python, beautifulsoup, DOM parsing)
   3. Programming a raspberry pi to send images over the internet into a database
      1. How to use REST APIS and making http calls
      2. sending requests, json formatting
   4. Setting up a web app to handle requests
      1. writing request handler
      2. authentication/identification
      3. saving request contents to database
6. What is image labeling and object detection?
   1. How are images labeled?
   2. What technologies are used for image recognition? What is a CNN?
   3. How to train a CNN?
   4. Transfer learning and pretrained classifiers
   5. How to use PIL, openCV, python for image processing
7. Teambuilding: communicating in limited channels

### Kite Flying and Optics

1. Kite photograpy
   1. What are the operational and safety considerations?
   2. Payload size, weight, and power (SWaP)
   3. Best practices for launching a kite
2. Optics and spectral nature of light
   1. Light, energy, photons, Blackbody radiation
   2. Spectrum of light
   3. Absorption, Reflectivity
   4. Camera sensors, channels
   5. Multispectral sensing
3. Converting a webcam into near-field IR camera
4. Raspberry Pi
   1. How to connect to Raspberry Pi
   2. Loading programs
   3. Connecting a webcam
   4. Taking images with the webcam and saving
5. Visualizing and analyzing multispectral images
   1. Using openCV to analyze each channel
   2. Compute photosynthesis levels with NDVI
   3. Accounting for white balance  
6. Kite photography exercise
   1. Students take the raspberry pi cameras they built the previous days, alongside some gopros/other cameras, attach to kites, fly and take aerial images
   2. Students address issues with stabilization, payload, etc.

### Decision Making and Optimization

1. Decision making
   1. What decisions need to be made in HADR applications?
   2. Who makes those decisions?
   3. What information is necessary to support decisions?
   4. What costs/benefits/constraints are considered?
   5. What is optimization? What kind of optimization problems are there?
   6. How to sort data?
2. What optimization problems can be done on graphs?
   1. What is optimization?
   2. Why is optimization difficult?
   3. Combinatorial difficulty, integer problems
   4. What kinds of optimization problems are there?
      1. Shortest path problems
      2. Routing problems
      3. Sensor placement/knapsack
3. Traveling salesman problem (TSP)?
   1. What approaches are there to TSP?
   2. What variations are there of TSP?
   3. How to implement a solution to TSP (greedy) in python (networkx)
   4. How to improve on greedy solution
4. Knapsack problem
   1. Formulation
   2. Applications in real world: budgets, scheduling
   3. Approaches: greedy, discuss edge cases where greedy fails
5. What are job-shop scheduling problems (JSP)?
   1. How can they be represented on a graph?
   2. What can be modeled as JSP?
   3. What approaches can you take for JSP?
   4. How to implement a solution to JSP? How to improve?
6. Exercise: implement greedy approach, see if they can improve
   1. Lecture + Teambuilding exercise: Sorting algorithms
   2. Teambuilding exercise, phase I: students are to line up by age, increasing. Timed.
   3. Lecture: sorting algorithms
       1. big O() complexity
       2. data structures
       3. simple sort algorithms, incl. heapsort
   4. Teambuilding part II: each student is given a random number, need to sort by number, increasing. Timed again.
   5. Discussion – were they able to improve on their time from part I?
      1. Part III: repeat one last time the sorting exercise, except the students get to discuss and plan for up to 5 minutes beforehand. They get new random numbers, and have to sort again.
   6. Discussion, were they able to improve given prep time? What things helped/didn&#39;t help?
      1. Goal of part I -\&gt; part II is to teach the benefit of doing things with more efficient algorithm. Goal of part II -\&gt; part III is the teach benefit of communication, planning, and setting responsibilities.

### Supplemental

1. What are some classical engineering failures? What went wrong?
2. What is uncertainty? How can we model and characterize uncertainty?
3. What is classification? What are some techniques for classification (decision trees, K-NN)?
4. What is regression? What are some techniques for regression (linear, kernel)?
5. What is uncertainity? How do we characterize it (bootstrap, random forest, Gaussian models)?
6. History of image recognition
   1. Imagenet large scale visual recognition challenge
   2. Convolutional neural networks
   3. image labeling tasks
   4. existing datasets
7. Labeling images
   1. Types of annotation: scene, point, polygon
   2. Need for labels/data set for HADR
   3. Manually labeling data
8. Pretrained image labelers
   1. Open source implementations
   2. Commercial implementations
   3. Transfer learning
   4. Using labels in decision making

### Field Trips - 2019

#### MIT Lincoln Laboratory

1. What HADR research does MIT Lincoln Laboratory do?
2. What kinds of data do we collect?
3. What tools do we use?
4. What problems do we address?
5. What backgrounds do we have?

#### Massachusetts Task Force One (MA-TF1)

1. What is MA-TF1 and what do they do?
2. What is their role in FEMA and organizational structure?
3. How to they prepare?
4. What tools do they use?
5. What challenges do they face?
6. What opportunities are there to use sensing and data?

#### Draper Laboratory

1. What was Draper's role in the Apollo moon program?
2. What is Draper doing now for manned space flight?
3. Fly the full size lunar landing simulator.

## Useful Links and References

1. Beaver Works Summer Institute (BWSI)  
   1. [BWSI Homepage](https://beaverworks.ll.mit.edu/CMS/bw/bwsi)
   2. [BWSI Twitter (@MITBeaverworks)](https://twitter.com/MITBeaverworks)
   3. [BWSI Twitter (@BWSI3)](https://twitter.com/bwsi3)
   4. [BWSI Instagram (@BWSI3)](https://www.instagram.com/BWSI3/)
   5. [BWSI Remote Sensing 2019 Instagram (remote_sensing_2019)](https://www.instagram.com/remote_sensing_2019/)
   6. [BWSI YouTube Channel](https://www.youtube.com/channel/UCZ6aVlpRXxU7uR4NBRAYvzQ)
2. MIT Lincoln Laboratory (MIT LL)  
   1. [MIT LL Homepage](https://www.ll.mit.edu/)  
   2. [MIT LL Twitter (@MITLL)](https://twitter.com/MITLL)
   3. [MIT LL Instagram (@lincoln_laboratory)](https://www.instagram.com/lincoln_laboratory/)
3. Python Like You Mean It (PLYMI)
   1. [PLYMI Homepage](https://www.pythonlikeyoumeanit.com/)
   2. [GitHub hosted source](https://github.com/rsokl/Learning_Python)
4. Geospaital Information Systems (GIS)
   1. [Automating GIS Process - 2018](https://automating-gis-processes.github.io/2018/)
5. Public Lab
   1. [Public Lab Homepage](https://publiclab.org/)
   2. [Infragram](https://publiclab.org/wiki/infragram)
   3. [Infragram - Raspberry Pi Deployment](https://publiclab.org/wiki/raspberry-pi-infragram)

## Distribution Statement

DISTRIBUTION STATEMENT A. Approved for public release. Distribution is unlimited.

(C) 2019 Massachusetts Institute of Technology.

Delivered to the U.S. Government with Unlimited Rights, as defined in DFARS Part 252.227-7013 or 7014 (Feb 2014). Notwithstanding any copyright notice, U.S. Government rights in this work are defined by DFARS 252.227-7013 or DFARS 252.227-7014 as detailed above. Use of this work other than as specifically authorized by the U.S. Government may violate any copyrights that exist in this work.
