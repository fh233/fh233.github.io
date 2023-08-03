---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# Greetings!
This is Feng. I am currently a graduate student at Rutgers, The State University of New Jersey. My research interest includes dynamics, control and machine learning and its application in robotics. I am conbining the maching learning-based tools for robotics motion planning and control. I have been working on autonomous bicycle, mobile manipulation, agile maneuvering control and other underactuated balancing robots. 

# 📖 Educations

- Ph. D., Mechanical Engineering, Rutgers University September, 2019-Now
- M. S., Aerospace Engineering, Harbin Institute of Technology (China), June 2019
- B. S., Aerospace Engineering, Nanjing University of Aeronautics and Astronautics (China), June 2017


# Research Interests

- Robotics and autonomous systems (autonomous vehicles, manipulation, robot dynamics and control)

- Dynamic systems and control (machine learning-based modeling and control, nonlinear control system design,  design and control of mechatronic systems)

- Learning-based sensor fusion and posture analysis
(learning-based sensor data analysis and modeling, 
gait/posture detection and prediction)


# Teaching Experience
*Fall 2019 – Now*, Department of Mechanical and Aerospace Engineering, Rutgers University<br /> 

- MAE 401: Dynamics Systems and Control (*Summer 2020, 2021, 2022*), Instructor
- MAE 361: Introduction to Mechatronics Lab (*Fall 2022, Spring 2023*), Instructor
- MAE 365: Dynamics (*Fall 2021*), Teaching Assistant



# 🎖 Honors and Awards

<figure>
    <img  src='images/award.jpg' alt='missing' width= "300" class="center"/>
    <figcaption>Award Ceneramy on at 2023 IEEE/ASME AIM Conference, Seattle, WA</figcaption>
</figure>


<p><img src='images/award.jpg' alt="sym" width="800" class="center"><br /><p>
- *2023*, Best Transaction Paper of IEEE/ASME Transaction on Mechatronics (Finalist)

- *2019*, Graduate Fellowship, Department of Mechanical and Aerospace Engineering, Rutgers.
- *2017-2018*, Graduate Fellowship, Harbin Institute of Technology, 
- *2017*, National Scholarship, Nanjing University of Aeronautics and Astronautics, 
- *2013-2017*, Outsdanding students fellowship, Nanjing University of Aeronautics and Astronautics



# 📝 Projects 

<b> 1. Lenaring-based control for underactuatd balcne robots </b><br /> 
For the uncertainites and modelling errors, a Gaussian Process based maching learning framewrok has been proposed to deal with modelling and contorl. The learning based method is integreated with EIC-based control for underactuated balance robots. Somultaneously we can achieve trajectorying tracking and balacne control.

<b> 2. Ski-stunt Maneuvering Control of Racing Truck </b><br /> 


<div class="auto-resizable-iframe">
  <div>
    <iframe frameborder="0" allowfullscreen="" src="https://www.youtube.com/embed/UNvMRVXNZ0U"></iframe>
  </div>
</div>
<br /> 
<div class='paper-box-text' markdown="1">

A ski-stunt maneuver is a type of aggressive vehicle motions in which a four-wheel vehicle runs on two wheels on one side.  We present the safety-guaranteed motion control of  autonomous ski-stunt maneuvers. (see the video abvoe)



<b> 3. Cordinated Control of Mobile Robot </b><br /> 
- autonomous bicycle robot control for crossing obstacles with impulsive actuation

<div class="auto-resizable-iframe">
  <div>
    <iframe frameborder="0" allowfullscreen="" src="https://www.youtube.com/embed/cyA_f5utthc"></iframe>
  </div>
</div>
<br /> 
<div class='paper-box-text' markdown="1">

As a single-track mobile platform, bikebot (i.e., bicycle-based robot) has attractive capability to navigate through narrow, off-road terrain. However, running crossing step-like obstacles creates challenges. This project presents a novel autonomous bikebot control with two assistive legs to navigate crossing obstacles. (see the video abvoe)

- coordinate control of a manipulator on a bicycle robot control 

We present a coordinated pose control of mobile manipulation with the stationary bikebot. A coordinated planning and control design is presented to determine the balance-prioritized posture control under kinematic and dynamic constraints. <a href="https://www.youtube.com/watch?v=jHQRNrrnPMc&ab_channel=FengHan"> Video</a>


<b> 4. Learning-Based Motion Pattern Recogniztion and Control </b><br /> 

Using a recurrent neural network (RNN) with long short-term memory (LSTM) cells. to idenfity the human/animal gait and predict the poses in the real time with only IMU (Inertial Measurement Unit) measurement avaiable.




# 📝 Publications 

<b> Journals </b>

- F. Han, and J. Yi, Safe Motion Control of Autonomous Vehicle Ski-Stunt Maneuvers. <b>*IEEE/ASME Trans. on Mechatronics, 2023*</b>. (*Under Review*)

- P. Wang, F. Han, and Yi, Jingang, "Gyroscopic Balancer-Enhanced Motion Control Of An Autonomous Bikebot," in <b>*Journal of Dynamic Systems, Measurement, and Control*</b>, pp. 1-15, 2023. <a href="https://asmedigitalcollection.asme.org/dynamicsystems/article/doi/10.1115/1.4063014/1164571"> Link</a>


- F. Han, X. Huang, Z. Wang, J. Yi and T. Liu, "Autonomous Bikebot Control for Crossing Obstacles With Assistive Leg Impulsive Actuation," in  <b>*IEEE/ASME Transactions on Mechatronics*</b>, vol. 27, no. 4, pp. 1882-1890, Aug. 2022. <a href="https://ieeexplore.ieee.org/abstract/document/9781431/"> Link</a>

- F. Han, A. Jelvani, J. Yi and T. Liu, "Coordinated Pose Control of Mobile Manipulation With an Unstable Bikebot Platform," in <b>*IEEE/ASME Transactions on Mechatronics*</b>, vol. 27, no. 6, pp. 4550-4560, Dec. 2022. <a href="https://ieeexplore.ieee.org/abstract/document/9750394/"> Link</a>


- F. Han and J. Yi, "Stable Learning-Based Tracking Control of Underactuated Balance Robots," in <b>*IEEE Robotics and Automation Letters*</b>, vol. 6, no. 2, pp. 1543-1550, April 2021. <a href="https://ieeexplore.ieee.org/abstract/document/9345449/"> Link</a>


- T. Yigit, F. Han, E. Rankins, J. Yi, K. H. McKeever and K. Malinowski, "Wearable Inertial Sensor-Based Limb Lameness Detection and Pose Estimation for Horses," in <b>*IEEE Transactions on Automation Science and Engineering*</b>, vol. 19, no. 3, pp. 1365-1379, July 2022. <a href="https://ieeexplore.ieee.org/abstract/document/9743494"> Link</a>



<b> Conference </b><br /> 

- T. Zheng, F. Han, and J. Yi, Design and Control of An Agricultural Robot for Turf Grass Inspection. 2023 Modeling, Estimation and Control Conference. (*Accepted*)


- F. Han and J. Yi, "On the Learned Balance Manifold of Underactuated Balance Robots," *2023 IEEE International Conference on Robotics and Automation (ICRA)*, London, United Kingdom, 2023, pp. 12254-12260. <a href="https://ieeexplore.ieee.org/abstract/document/10161088/"> Link</a>

- F. Han and J. Yi, "Learning-based Safe Motion Control of Vehicle Ski-Stunt Maneuvers," *2022 IEEE/ASME International Conference on Advanced Intelligent Mechatronics (AIM)*, Sapporo, Japan, 2022, pp. 724-729. <a href="https://ieeexplore.ieee.org/abstract/document/9863309/"> Link</a>

- C. Deng, Y. Gong, F. Han, S. Liao, J. Yi and B. Yuan, "VLSI Hardware Architecture for Gaussian Process," *2020 54th Asilomar Conference on Signals, Systems, and Computers*, Pacific Grove, CA, USA, 2020, pp. 121-124. <a href="https://ieeexplore.ieee.org/abstract/document/9443272"> Link</a>

- M. Mihalec, F. Han, and J. Yi, "Integrated inverted pendulum and whole-body control design for bipedal robot with foot slip," *IFAC-PapersOnLine*,
Volume 55, Issue 37, pp. 376-381, 2022. <a href="https://www.sciencedirect.com/science/article/pii/S2405896322028555"> Link</a>

- X. Huang, F. Han, Y. Han, S. Wang, T. Liu and J. Yi, "Motion Control of an Autonomous Wheel-Leg Bikebot," *2022 IEEE 18th International Conference on Automation Science and Engineering (CASE)*, Mexico City, Mexico, 2022, pp. 2341-2346. <a href="https://ieeexplore.ieee.org/abstract/document/9926543/"> Link</a>

- C. Zhu, F. Han and J. Yi, "Wearable Sensing and Knee Exoskeleton Control for Awkward Gaits Assistance," *2022 IEEE 18th International Conference on Automation Science and Engineering (CASE)*, Mexico City, Mexico, 2022, pp. 2393-2398. <a href="https://ieeexplore.ieee.org/abstract/document/9926655"> Link</a>


- T. Yigit, F. Han, E. Rankins, J. Yi, K. McKeever and K. Malinowski, "Wearable IMU-based Early Limb Lameness Detection for Horses using Multi-Layer Classifiers," *2020 IEEE 16th International Conference on Automation Science and Engineering (CASE)*, Hong Kong, China, 2020, pp. 955-960. <a href="https://ieeexplore.ieee.org/abstract/document/9216873"> Link</a>




# Professional Avtivities

<b> Reviewer for </b>
- Journals: IEEE Trans. on Automation Science and Engineering, IEEE Trans. on Control Systems Technology, IEEE/ASME Trans. on Mechatronics, IEEE Robotics and Automation Letters, Control Engineering Practice, Mechatronics, Transportation Research Part C, International Journal of Intelligent Robotics and Applications, IEEE Transa. on Human-Machine Systems, 

- Conferences: American Control Conference (ACC), IEEE/ASME International Conference Advanced Intelligent Mechatronics (AIM), IEEE International Conference on Automation Science and Engineering (CASE), IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), IEEE International Conference on Intelligent Transportation Systems (ITSC), IEEE International Conference on Robotics and Automation (ICRA), IFAC

<b> Graduate Student Member of </b> <br /> 
American Society of Mechanical Engineers (ASME),  Institute of Electrical and Electronics Engineers (IEEE) 
 
# Intrests and Hobbies 

- Cooking
- Travel
- Phtographa, see my photo gallery  <a href="https://feltonhan.github.io"> see my photo gallery</a> <br /> <br /> 