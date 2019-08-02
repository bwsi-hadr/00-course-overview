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
   * History and mission of CAP
   * What information does aerial imagery provide?
   * What challenges are there in dealing with aerial imagery?
   * What goes into planning CAP missions? Elevation, distance, path, targets
2. What kind of information is available from satellite imagery, and how is it used?
   * Sources of public imagery
   * Sensing bands
   * Preprocessing, Calibration
   * Analyses, uses, limitation
3. Imagery data
   * How are images represented on a computer?
   * What are pixels, channels? What do they represent?
   * What is metadata? EXIF?
   * Understanding color systems and decomposing images into channels: RGB, HSV
   * Understanding convolution kernal filters
   * Accounting for heading, orientation, distortion of aerial images
   * Stitching together images
4. Databases to store data
   * Why do we need databases?
   * SQL and noSQL databases
   * Queries, Inserts, Joins, Updates
   * Setting up a web server
5. Internet of Things (IoT)
   * What are web apps, how are they structured?
   * Scraping data from websites (Python, beautifulsoup, DOM parsing)
   * Programming a raspberry pi to send images over the internet into a database
      - How to use REST APIS and making http calls
      - sending requests, json formatting
   * Setting up a web app to handle requests
      - writing request handler
      - authentication/identification
      - saving request contents to database
6. What is image labeling and object detection?
   * How are images labeled?
   * What technologies are used for image recognition? What is a CNN?
   * How to train a CNN?
   * Transfer learning and pretrained classifiers
   * How to use PIL, openCV, python for image processing
7. Teambuilding: communicating in limited channels