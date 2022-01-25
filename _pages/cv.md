---
layout: archive
title: "Sai Abhishek Siddhartha Namburu"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Master of Science in Mechanical Engineering, Carnegie Mellon University, Concentration: Robotics and Control, 2021-2023 [current GPA: 4.0/4.0]
* B.E. (Hons.) Mechanical Engineering, Birla Institute of Technology and Science (BITS) Pilani - India, 2015-2020 [GPA: 8.74/10]

Work experience
======

* **September 2021 - Present:** Graduate Research Assistant
  * **Location:** Human Sensing Lab, Carnegie Mellon University
  * **Description:** 
       * Modified current deep mind based I3D action recognition model(with non-local blocks) to localize activity and achieved an accuracy of 72% (in real domain) training on combination of synthetic and real robot cognition data.
       * Implemented Gradient Reversal Layer for I3D improving accuracy in real domain by 2% without using labels in real domain while training.
  * **[Code](https://github.com/namburusiddhartha/Action_recognition_with_GRL)** 
  * **Supervisor:** Professor [Fernando De La Torre](https://www.cs.cmu.edu/~ftorre/) and Prof. [Jessica K. Hodgins](https://www.cs.cmu.edu/~jkh/)
  
* **August 2020 - August 2021:** Machine Learning Engineer
  * **Location:** [DeepEdge](https://www.deepedge.ai/), Hyderabad - India
  * **Description** 
       * Developed a face recognition solution(SCRFD + ArcFace + Scale Adaptive KCF) for body cameras worn by security officials. Integrated the pipeline by developing an application in K7 Camera(Ambarella CV25 chip) to inference on real time data. [[code]](https://github.com/namburusiddhartha/Face-Recognition-system---Retinaface-Arcface) [[code]](https://github.com/namburusiddhartha/Retinaface)
       * Modified and trained a Mask-RCNN to detect custom objects, draw masks and identify keypoints of interest in pytorch. Improved inference speed by 3x by converting the model into TensorRT using TensorRT wrappers. [[code]](https://github.com/namburusiddhartha/Object-Detection-with-tensorRT) 
       * Accelerated Iterative Point Cloud algorithm (based on open3d) by 2.5x using cuda kernels and thrust library. [[code]](https://github.com/namburusiddhartha/ICP_with_cuda)
       * Analysed and calculated GAIT Characteristic parameters like stepcount, stance, swing from a pre-trained openpose pose detection model for an autonomous walker.

* **August 2020 - August 2021:** Project Assistant
  * **Location:** Indian Institute of Science, Bangalore - India 
  * **Description** 
       * Devised a structural optimization algorithm to optimize the shape of interface in heat exchanger to ensure maximun possible heat transfer between two liquids.
       * Developed thermal resistance networks in python and simulated FE flow in the heat exchanger.
       * Investigated effects of various design parameters and operating conditions on a s-CO2 compressor in a sub-scale s-CO2 system at IISc.
  * **Supervisor:** Professor [Anathasuresh](https://mecheng.iisc.ac.in/people/g-k-ananthasuresh/), Prof. [Pramod Kumar](https://mecheng.iisc.ac.in/people/pramod-kumar/)

* **July 2018 - December 2018:** Fintech Intern
  * **Location:** Nomura Services India Private Limited, Mumbai - India 
  * **Description** 
       * Assisted Nomura’s FinTech division: Responsible for conceptualization and execution of Nomura technology development program - Implemented AI/ML, NLP technologies to automate use-cases across various divisions.
       * Implemented an anomaly detection solution for finance division by testing and using HBOS (Histogram-Based Outlier Score) and DBSCAN (Density-based spatial clustering of applications with noise) for trade profiles to flag false trades.

* **May 2016 - July 2016:** Undergrad Research Intern
  * **Location:** Control Systems Lab, DRDO, Hyderabad - India 
  * **Description** 
       * Designed and re-modelled wing deployment mechanism of an unmanned air-vehicle featuring actuators, aerodynamic design of wing and fin assembly for different locking positions.
       * Proposed addition of new components which significantly decrease the potential risk in the air vehicle.
       * Validated the proposed assembly by conducting real time simulation study by using ANSYS Structural and Fluent.
* **Supervisor:** Dr [Rahul Dixit](https://www.linkedin.com/in/dr-rahul-dixit-4a101817/?originalSubdomain=in)


Projects
======
* **Emotion Recognition in Multi-Party Conversations using Multi-Modal Approach:** October 2021 -- November 2021
  * **Description:** 
      * Achieved an accuracy of 60% in predicting sentiment and emotion by combining text and audio modules of multi-party conversations in friends using shallow machine learning models.
      * Deployed various feature engineering methods to improve the accuracy by 5%. Compared the results with t-CNN, d-RNN and bc-LSTM and reasoned the accuracies.
  * **Tech Stack:** Python, PyTorch, Tensorflow
  * **[Code and Report](https://github.com/namburusiddhartha/24787-Project_Multi-Modal-Approach-for-Sentiment-Analysis)**

* **Robot Planner Visualization:** October 2021 -- November 2021
  * **Description:** 
      * Implemented RRT, RRT*, RRT Connect, A*, Weighted A* and Dijikstra in 2D using object oriented paradigm.
      * Visualized the search of these planner using openGL in 2D. Developed a GUI to make the product market ready.
  * **Tech Stack:** C++, openGL
  * **[Code and Report](https://github.com/namburusiddhartha/Path_Planning_open_GL)**

* **Computer Vision Assignments:** August 2021 -- November 2021
  * **Description:** 
      * Implemented visual object tracking with Lucas-Kanade forward additive image alignment algorithm and Matthew-Bakers Inverse Compositional alignment algorithm.
      * Performed 3-D Reconstruction of a temple estimating Fundamental matrix using with 8/7-point algorithm and RANSAC.
      * Worked on stitching panoramas utilizing homography and RANSAC.
      * Implemented MNIST character detection recognition using neural nets and acheived an accuracy greater than 90%
      * Used Spatial Pyramid Matching of image word maps to recognise the location of an image.
  * **Tech Stack:** Python, PyTorch
  * **[Code and Report](https://github.com/namburusiddhartha/Computer_Vision_assignments)**

* **Home Service Robot:** June 2021 – July 2021
  * **Description:** 
      * Deployed a turtlebot mobile robot in a designed custom environment in gazebo to pick-up and drop-off objects in the environment.
      * Mapped the environment using gmapping package, localized it and used ROS navigation stack (Dijkstra’s algorithm) to plan a safe path to pick-up and drop-off objects (designed with rviz marker).
  * **Tech Stack:** C++, ROS

* **Fashion Retail forecasting using ENN:** February 2019 – April 2019
  * **Description:** 
      * Modelled custom evolutionary neural network using genetic algorithm to forecast demand for two different apparels.
      * Employed a pre-search algorithm along with BIC metric to effectively increase computation speed.
      * Compared with a Non-linear Auto Regressive exogenous input network to pick a better forecasting method.
  * **Tech Stack:** Python, Keras, Scikit-learn, Matlab DL tool
  * **[Code](https://github.com/namburusiddhartha/Fashion-retail-forecasting)** 
  
* **Classification of YouTube comments to detect advertisements:** November 2017 - December 2017
  * **Description:** 
      * Implemented an end-end approach with Support Vector Machine and a Naive Bayes classifier to classify YouTube comments and detect advertisements based on words used.
      * Used RoC-AuC metric to tune hyperparameters in the model.
  * **Tech Stack:** Python
  * **[Code](https://github.com/namburusiddhartha/Youtube-comment-classification)** 
  
* **Neural Style transfer and face recognition for the Happy house:** September 2018 - October 2018
  * **Description:** 
      * Used a pre-trained FaceNet system that utilizes a deep convolution net and stochastic gradient descent, implementing the triplet loss function to recognize faces.
      * Implemented the Neural style transfer algorithm utilizing VGG-16 that merges content and style images to create a generated image.
      * Computed cost function using the Gram matrix of that layer’s activations. The overall style cost function is obtained using several hidden layers.
  * **Tech Stack:** Python, tensorflow
  * **[Code](https://github.com/namburusiddhartha/Neural-Style-transfer)** 

* **Algorithm to reduce epicyclic geartrains by Isomorphism test:** February 2018 – April 2018
  * **Description:** 
      * Devised an algorithm to reduce the number of epicyclic gear trains after checking structural and rotational isomorphism.
      * Algorithm first generates all possible Epi cyclic gear trains(EGT) and associates each them to a matrix using hammingmethod, then checks for translational and rotational isomorphism retaining non-isomorphic gear trains.
  * **Tech Stack:** Matlab

* **Constitutive modelling and processing map analysis of different alloys:** Jan 2017 -- May 2018
  * **Description:** 
      * Modified and modelled different constitutive equations - JC, ZA, Arrhenius, KHL and RK to different heavy alloys of tungsten and EDD steel at elevated temperatures and wide range of strain rates.
      * Implemented a partially-trained neural network in a central way in an iterative non-linear finite element analysis of the test specimen in order to extract approximate, but gradually improving, stress–strain information with which to train the neural network.
  * **Tech Stack:** Matlab

Skills
======
* **Programming Languages:**  Python, C/C++ (Cuda kernels and thrust library), Java, R
* **Deep-Learning Frameworks:**  PyTorch, TensorRT, Keras, Tensorflow(1 and 2), Caffee, MXNet
* **Tools:**  Docker, Scikit learn, OpenCV, SQL, MS Office, LaTeX, GitHub
* **Application Software:** ROS, MATLAB, Gazebo, ANSYS (CFD and FEA), COMSOL, AxSTREAM, Solidworks, Creo

Publications
======
<!--   <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
  * [Constitutive modelling and processing map analysis of tungsten heavy alloy (92.5W-5.25Ni-2.25Fe) at elevated temperatures, Second author, International Journal of Refractory Metals and Hard Materials](https://www.sciencedirect.com/science/article/abs/pii/S0263436818303469)
  * [Algorithm to reduce epicyclic gear trains by testing for Isomorphism](https://drive.google.com/file/d/1FMFuYCh4md1BE73OmBuI2IrwNaIZ--zF/view)

  
Research & Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Certificates & Achievements
======
* **Robotics Software Engineer :** Udacity \[In Progress]
* **Deep Learning Specialization:** Deeplearning.ai, Coursera \[December 2018]
* **Machine Learning:** Coursera \[December 2018]
* **C, C++, Java programming**: NIIT \[May 2019]
* **Excel to My SQL Analytics techniques:** Coursera \[Jun 2018]
* **Bloomberg Market Concepts:** Bloomberg \[Aug 2017]
* **R programming training:** Innodatatics USA \[Aug 2017]

Activities and Interests
======
* **Secretary at Brindavanam Telugu Samithi** at BITS-Hyderabad
* **Member of VFX Club** at BITS-Hyderabad
* **Member of Department of Visual Effects** at BITS-Hyderabad
* **Teaching Volunteer** for nearby schools in under-developed areas as a part of Nirmann, BITS Hyderabad

<!-- Activities and Interests
======
* Currently signed in to 43 different slack teams -->
