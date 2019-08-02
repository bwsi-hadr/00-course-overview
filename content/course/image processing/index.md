---
title: 'Image Processing'
date: 2019-01-01T00:00:00+10:00
weight: 103
---

The first application of knowledge in the Remote Sensing course involves image processing. Students use satellite imagery and other aerial photos to analyze the Earth. Students learn about how aerial images are taken and about how to analyze different types of images.

### Github Repos

[06-Intro-to-Image-processing](https://github.com/bwsi-hadr/06-Intro-to-Image-processing)  
[07-Satellite_Image_Processing_Using_Python](https://github.com/bwsi-hadr/07-Satellite_Image_Processing_Using_Python)

## Topics Covered

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