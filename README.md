# 00-course-overview

Course overview, syllabus, schedule, etc. for the Beaver Works Summer Insitute (BWSI) summer remote sensing course

## Course Overview

The Beaver Works Summer Institute will offer students the opportunity to explore the exciting intersection of data science and crisis response. During the course, the students will learn to understand the basics of Python, Git, data science, machine learning, and image processing. Students will explore real world datasets ranging from drone imagery of regions to disaster imagery collected by the human volunteers of the Civil Air Patrol. Students will develop experience in an area of data science that is poised to play a critical role in understanding our world.

## Syllabus  

This syallabus is a high level outline and subject to change over the duration of the course.  

### Week 1: Introduction + Python  

#### Day 1: Introduction to Remote Sensing for Humanitarian Assistance and Disaster Relief (HADR)  

###### Learning Objectives  

1. What is this course about? Who is everybody?
2. What is Remote Sensing?
3. Why do we need to sense things?
4. What is HADR? Who provides HADR?

##### Lecture and Exercise  

1. Ice Breaker
   1. Everyone writes an interesting fact about them on a piece of paper and puts it in a bucket. Everyone draws a piece of paper from the bucket and tries to find the person the fact belongs to
2. What is Emergency Management Lecture
   1. The roles of various agencies/levels
   2. Tasks required of agencies
   3. Core concepts
   4. Scenario-based planning
   5. What information is needed to plan and respond?
3. Exercise: Sensing modalities brainstorming
   1. Identify quantities that may be useful for sensing in emergency situations
   2. How could you sense those quantities? e.g. visual, particulate, temperature, conductivity
   3. What limitations do you have? e.g. power/comms requirement, occlusion, calibration, noise, resolution, observability
   4. What are the costs?
   5. Community/crowdsourcing – how to task people to help with sensing? What considerations do you need to take into account? Safety, accuracy, trustworthiness, bias

#### Day 2: Introduction to Python (a review)

##### Learning Objectives  

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
   2. filtering
   3. joining, pivoting
6. Visualizing data
   1. matplotlib, histograms, heatmaps, imshow
   2. time series, graphs

##### Lecture and Exercises  

1. Setup of development environment
2. Loading data into numpy, pandas
3. Filtering data, logical indexing
4. Computing statistics
5. Plotting and visualizing data

#### Day 3: Field Trip to MIT Lincoln Laboratory

##### Learning Objectives

1. What do we do at Lincoln for HADR?
2. What kinds of data do we collect?
3. What tools do we use?
4. What problems do we address?
5. What backgrounds do we have?

##### Lectures/Demos  

1. MIT LL Overview
2. Water and Mechanical engineering  
3. Hurricane Response
4. Satellite calibration 
5. Civil Air Patrol 
6. FEMA Remote Sensing/LIDAR

#### Day 4: Geographic Information Systems in Python

##### Learning Objectives

1. What is geographic information system (GIS)?
2. How to use GeoPandas
3. How to load various GIS file formats
4. How to load raster files with GDAL
5. How to create a map with layers
6. How to do spatial calculations
7. ICRC Guest speaker

##### Lecture topics and Exercises

1. Loading basemaps from repositories
2. Loading shapefiles of data layers
3. Geometric operations for overlays, intersection, union, etc
4. Reclassifying data
5. Loading raster files
6. Computing nearest neighbors, distances, spatial averages, spatial join
7. Machine Learning and forecast-based financing 

##### Resources  

[https://automating-gis-processes.github.io/2018/](https://automating-gis-processes.github.io/2018/)

[https://automating-gis-processes.github.io/2016/Lesson7-overview.html](https://automating-gis-processes.github.io/2016/Lesson7-overview.html)

#### Day 5: GIS and Networks in Python

##### Learning Objectives

1. What are networks?
2. How to use networkx
3. How to get network data from Open Street Maps?
4. What math can be done on networks, how do these algorithms work?
5. How to visualize networks in GIS?

##### Lecture topics and Exercises

1. Network properties: edges, vertices, adjacency, matrix representations
2. Shortest path, Djikstra&#39;s algorithm, shortest path tree, minimum spanning tree, centrality
3. Plotting measurements on the network
4. Converting graph to geodataframe
5. Exporting to raster, shapefile

##### Resources  

[https://automating-gis-processes.github.io/2018/](https://automating-gis-processes.github.io/2018/)

[https://automating-gis-processes.github.io/2016/Lesson7-overview.html](https://automating-gis-processes.github.io/2016/Lesson7-overview.html)

### Week 2: Data Science and Analysis

#### Day 6: Introduction to Engineering Design/Databases

##### Learning Objectives

1. What is engineering design?
2. How to identify requirements, constraints, and problems?
3. How to effectively communicate between teams?
4. How can engineering projects fail? What causes failures? How do we learn from failures?
5. How to store and access data in a database for analysis?

##### Lectures and exercises

1. Engineering design lecture 
   1. Overview of engineering design
   2. Case studies
   3. Failure analyses, post-mortem
2. Emergency Management: Matching the tool to the task
3. Teambuilding Exercise on Communication 
4. Database technologies 
   1. Why do we need databases?
   2. SQL and noSQL databases
   3. Queries, Inserts, Joins, Updates
   4. Setting up a web server

#### Day 7: Introduction to Data Science

##### Learning Objectives

1. How is data used to make decisions?
2. What is classification? What are some techniques for classification?
   1. How to use decision trees, K-NN
3. What is regression? What are some techniques for regression?
   1. Linear regression, kernel regression
4. What is uncertainty? How can we model and characterize uncertainty
   1. bootstrap, random forest, Gaussian models

##### Lectures and exercises

1. Classification
   1. Examples of classification tasks
   2. Decision tree
   3. K-Nearest Neighbors
   4. Curse of dimensionality
2. Regression
   1. Linear regression
   2. Kernel regression
3. Uncertainty
   1. Confidence intervals, error bars
   2. Bootstrap resampling
   3. Random forests

#### Day 8: MA-TF1 Field Trip

##### Learning Objectives

1. What is MA-TF1 and what do they do?
2. What is their role in FEMA and organizational structure?
3. How to they prepare?
4. What tools do they use?
5. What challenges do they face?
6. What opportunities are there to use sensing and data?

##### Tour  

1. Tour of MA-TF1 site
2. Overview of responsibilities, organization, capabilities
3. Examples of missions, tasks, training

#### Day 9: Images, metadata, and image processing

##### Learning Objectives

1. How are images represented on a computer?
2. What are pixels, channels? What do they represent?
3. How to use PIL, openCV, apply filters
4. What is metadata? EXIF?
5. Understanding color systems: RGB, HSV
6. Understanding convolutions

##### Lectures and exercises  

1. Loading images in python and opencv
2. Reading metadata and EXIF
3. Decomposing images into channels
4. Resizing and distorting images
5. Convolution kernel filters

#### Day 10: Images, image recognition, labeling

##### Learning Objectives

1. What is image labeling and object detection?
2. How are images labeled?
3. What technologies are used for image recognition? What is a CNN?
4. How to train a CNN?
5. Transfer learning and pretrained classifiers

##### Lectures and exercises

1. History of image recognition
   1. Imagenet large scale visual recognition challenge
   2. Convolutional neural networks
   3. image labeling tasks
   4. existing datasets
2. Labeling images 
   1. Types of annotation: scene, point, polygon
   2. Need for labels/data set for HADR
   3. Manually labeling data
3. Pretrained image labelers
   1. Open source implementations
   2. Commercial implementations
   3. Transfer learning
   4. Using labels in decision making

### Week 3: Aerial Imagery and Sensing

#### Day 11: Civil AIr Patrol and Aerial imagery

##### Learning Objectives

1. What is the Civil Air Patrol (CAP)?
2. What information does aerial imagery provide?
3. What challenges are there in dealing with aerial imagery?
4. What goes into planning CAP missions? Elevation, distance, path, targets
5. Teambuilding: communicating in limited channels
6. What kind of information is available from satellite imagery, and how is it used?

##### Lectures and exercises

1. History and mission of CAP
   1. Usage of CAP in emergency management
   2. Real-world CAP examples
2. Airplanes, mission planning
   1. Considerations and constraints for missions
3. Teambuilding exercise: communication across limited channels
4. Satellite imagery
   1. Sources of public imagery
   2. Sensing bands
   3. Preprocessing, Calibration
   4. Analyses, uses, limitations

#### Day 12: Building a hardware multispectral sensor

##### Learning Objectives

1. Understand the spectral nature of light; the relationship between wavelengths, energy, and visibility; long and short-wave radiation
2. Why do we want to sense at different wavelengths?
3. How to modify a camera to sense at near-field IR?
4. How to use and program a raspberry pi to take and save pictures using a webcam
5. Visualizing and analyzing multispectral data

##### Lectures and Exercise

1. Optics
   1. Light, energy, photons, Blackbody radiation
   2. Spectrum of light
   3. Absorption, Reflectivity
   4. Camera sensors, channels
   5. Multispectral sensing
2. Converting a webcam into near-field IR camera
3. Raspberry Pi
   1. How to connect to Raspberry Pi
   2. Loading programs
   3. Connecting a webcam
   4. Taking images with the webcam and saving
4. Visualizing and analyzing multispectral images
   1. Using openCV to analyze each channel
   2. Compute photosynthesis levels with NDVI
   3. Accounting for white balance  

##### Resources  

[https://publiclab.org/wiki/raspberry-pi-infragram](https://publiclab.org/wiki/raspberry-pi-infragram)

[https://publiclab.org/wiki/infragram](https://publiclab.org/wiki/infragram)

#### Day 13: Draper Field Trip and Kite Photography

##### Learning Objectives

1. History of satellites, space travel
2. Ongoing work in satellites
3. How to collect aerial photos using kites
4. What operational considerations are there for kite photography? Stabilization, payload weight, wind speed, elevation, optics

##### Tour and Exercise

1. Draper tour
2. Kite photography exercise
   1. Students take the raspberry pi cameras they built the previous days, alongside some gopros/other cameras, attach to kites, fly and take aerial images
   2. Students address issues with stabilization, payload, etc.

#### Day 14: Internet of Things, analyzing aerial images

##### Learning Objectives

1. How to use REST APIs
2. Sending information into a database over the internet
3. What are web apps, how are they structured?

##### Lectures and Exercises

1. Scraping data from websites
   1. Python, beautifulsoup, DOM parsing
2. Programming a raspberry pi to send images over the internet into a database
   1. making http calls
   2. sending requests, json formatting
3. Setting up a web app to handle requests
   1. writing request handler
   2. authentication/identification
   3. saving request contents to database
4. Analyzing aerial images
   1. Accounting for heading, orientation, distortion/perspective
   2. Stitching together images
5. Modifying kites and sensors for redeployment
   1. mods to improve stability, reduce weight, etc
   2. Potentially additional sensors?

#### Day 15: Kite Photography, part 2 (+ possible overflow day)

##### Learning Objectives

1. Collect more aerial photographs
2. Make adjustments on sensors based on first day to improve image quality, flight quality

##### Activities and Exercises

1. Any previous overrun lectures/exercises that need extra time
2. Additional adjustments on sensors
3. Fly more kites
4. Analyze the images from the kites

### Week 4: Decision Making and Optimization

#### Day 16: Decision making and HADR

##### Learning Objectives

1. What decisions need to be made in HADR applications?
2. Who makes those decisions?
3. What information is necessary to support decisions?
4. What costs/benefits/constraints are considered?
5. What is optimization? What kind of optimization problems are there?
6. How to sort data?
7. Collaborative/group decision making?

##### Lectures and Exercises

1. Lecture: Decision making in HADR
   1. What decisions need to be made?
   2. Who makes those decisions?
   3. Information/data to support decisions?
   4. Costs/benefits/constraints?
   5. Real-world examples?
   6. Discussion about notable good and bad decisions that have been made, post-mortem on what went right/wrong.
2. Intro to optimization
   1. What is optimization?
   2. What kinds of optimization problems are there?
   3. Why is optimization difficult?
   4. Example: Knapsack problem
       1. formulate
       2. applications in real world: budgets, scheduling
       3. approaches: greedy, discuss edge cases where greedy fails
   5. Exercise: implement greedy approach, see if they can improve
3. Lecture + Teambuilding exercise: Sorting algorithms
   1. Teambuilding exercise, phase I: students are to line up by age, increasing. Timed.
   2. Lecture: sorting algorithms
       1. big O() complexity
       2. data structures
       3. simple sort algorithms, incl. heapsort
   3. Teambuilding part II: each student is given a random number, need to sort by number, increasing. Timed again.
1. Discussion – were they able to improve on their time from part I?
   1. Part III: repeat one last time the sorting exercise, except the students get to discuss and plan for up to 5 minutes beforehand. They get new random numbers, and have to sort again.
1. Discussion, were they able to improve given prep time? What things helped/didn&#39;t help?
   1. Goal of part I -\&gt; part II is to teach the benefit of doing things with more efficient algorithm. Goal of part II -\&gt; part III is the teach benefit of communication, planning, and setting responsibilities.

#### Day 17: Graph Optimization

##### Learning Objectives

1. What optimization problems can be done on graphs?
2. What makes these problems difficult?
3. What is the traveling salesman problem?
4. What approaches are there to TSP?
5. What variations are there of TSP?
6. How to implement a solution to TSP (greedy) in python (networkx)
7. How to improve on greedy solution

##### Lectures and Exercises

1. Lecture: Graph optimization problems
   1. Decisions on graphs
   2. Combinatorial difficulty, integer problems
   3. Examples of problems
      1. Shortest path problems
      2. Routing problems
      3. Sensor placement/knapsack
   4. Traveling salesman problem
      1. formulation
      2. applications
      3. approaches
2. Exercise: Implementing solution to TSP
   1. Implement greedy solution
   2. Try to improve on greedy solution
   3. Try to get best solution on random graph

#### Day 18: Job-Shop Scheduling problems

##### Learning Objectives

1. What are job-shop scheduling problems?
2. How can they be represented on a graph?
3. What can be modeled as JSP?
4. What approaches can you take for JSP?
5. How to implement a solution to JSP? How to improve?

##### Lectures and Exercises

1. Lecture: Job-shop scheduling problem
   1. Formulation
      1. How to represent as a graph
      2. what graph concepts can be useful in representing/solving the JSP?
   2. Applications
   3. Approaches
   4. Variants
2. Exercise: Implementing solution to JSP
   1. Baseline greedy solution
   2. Try to improve
   3. Solving real-life scheduling problems

#### Day 19: Review day

##### Lectures and exercises

1. Review of previous topics
2. Send out survey prior to see which topics students want more time to discuss/work on

#### Day 20: Final Exercise Overview and prep day

##### Lectures and exercises

1. Introduce the final project
   1. Simulated disaster scenario
   2. Roles and responsibilities of teams – form teams
   3. Walkthrough of rules, information, and decisions
   4. Mock runthrough of game
2. Prep time to develop tools for final project
   1. Separate into teams, discuss strategies
   2. Establish communication channels and protocols between teams
   3. Adapt tools from course for decision support

#### Day 21: Dress Rehearsal for Final Exercise

#### Day 22: Final Exercise

## Useful Links

1. Beaver Works Summer Institute (BWSI)  
   1. [BWSI Homepage](https://beaverworks.ll.mit.edu/CMS/bw/bwsi)
   2. [BWSI Twitter (@MITBeaverworks)](https://twitter.com/MITBeaverworks)
   3. [BWSI Twitter (@BWSI3)](https://twitter.com/bwsi3)
   4. [BWSI Instagram (@BWSI3)](https://www.instagram.com/BWSI3/)
   5. [BWSI YouTube Channel](https://www.youtube.com/channel/UCZ6aVlpRXxU7uR4NBRAYvzQ)
2. MIT Lincoln Laboratory (MIT LL)  
   1. [MIT LL Homepage](https://www.ll.mit.edu/)  
   2. [MIT LL Twitter (@MITLL)](https://twitter.com/MITLL)
   3. [MIT LL Instagram (@lincoln_laboratory)](https://www.instagram.com/lincoln_laboratory/)
3. Python Like You Mean It (PLYMI)
   1. [PLYMI Homepage](https://www.pythonlikeyoumeanit.com/)
   2. [GitHub hosted source](https://github.com/rsokl/Learning_Python)

## Distribution Statement

DISTRIBUTION STATEMENT A. Approved for public release. Distribution is unlimited.  

(C) 2019 Massachusetts Institute of Technology.  

Delivered to the U.S. Government with Unlimited Rights, as defined in DFARS Part 252.227-7013 or 7014 (Feb 2014). Notwithstanding any copyright notice, U.S. Government rights in this work are defined by DFARS 252.227-7013 or DFARS 252.227-7014 as detailed above. Use of this work other than as specifically authorized by the U.S. Government may violate any copyrights that exist in this work.  

