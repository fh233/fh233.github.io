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
This is Feng. Feng is currently a graduate student at Rutgers, The State University of New Jersey, since 2019. His research interest includes dynamics, control and machine learning and its application in robotics. Feng has been working on autonomous bicycle, mobile manipulation, agile maneuvering control and other underactuated balancing robots. 

# 📖 Educations

Ph. D., Mechanical Engineering, Rutgers University September, 2019-Now
M. S., Aerospace Engineering, Harbin Institute of Technology (China), June 2019
B. S., Aerospace Engineering, Nanjing University of Aeronautics and Astronautics (China), June 2017


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
- *2019*, Graduate Fellowship, Department of Mechanical and Aerospace Engineering, Rutgers.
- *2017-2018*, Graduate Fellowship, Harbin Institute of Technology, 
- *2017*, National Scholarship, Nanjing University of Aeronautics and Astronautics, 
- *2013-2017*, Outsdanding students fellowship, Nanjing University of Aeronautics and Astronautics



# 📝 Projects 

<b> Lenaring-based control for underactuatd balcne robots </b><br /> 


<b> Ski-stunt Maneuvering Control of Racing Truck </b><br /> 




<b> Cordinated Control of Mobile Robot </b><br /> 
- autonomous bicycle robot control for crossing obstacles with impulsive actuation <br /> 

<div class="auto-resizable-iframe">
  <div>
    <iframe frameborder="0" allowfullscreen="" src="https://www.youtube.com/embed/UNvMRVXNZ0U"></iframe>
  </div>
</div>
<br /> 
<div class='paper-box-text' markdown="1">

As a single-track mobile platform, bikebot (i.e., bicycle-based robot) has attractive capability to navigate through narrow, off-road terrain with high speed. However, running crossing step-like obstacles creates challenges for intrinsically unstable, underactuated bikebots. This project presents a novel autonomous bikebot control with two assistive legs to navigate crossing obstacles. The proposed design integrates the external/internal convertible form-based motion control with leg-assisted impulse actuation. The leg–terrain interaction generates impulsive torques to help maintain navigation and balance when running across obstacles. The control performance is analyzed and guaranteed. The experimental results confirm that under the control design, the bikebot can smoothly run crossing multiple step-like obstacles with heights more than one-third of the wheel radius. (see video above)

- coordinate control of a manipulator on a bicycle robot control  <br /> 

Bikebot manipulation has advantages of the single-track robot mobility and manipulation dexterity. We present a coordinated pose control of mobile manipulation with the stationary bikebot. The challenges of the bikebot manipulation include the limited steering balance capability of the unstable bikebot and kinematic redundancy of the manipulator. We first present the steering balance model to analyze and explore the maximum steering capability to balance the stationary platform. A balancing equilibrium manifold is then proposed to describe the necessary condition to fulfill simultaneous platform balance and posture control of the end-effector. A coordinated planning and control design is presented to determine the balance-prioritized posture control under kinematic and dynamic constraints. Extensive experiments are conducted to demonstrate the mechatronic design for autonomous plant inspection in agricultural applications. The results confirm the feasibility to use the bikebot manipulation for plant inspection with end-effector position and orientation errors about 5 mm and 0.3 degs, respectively.


<b> Learning-Based Motion Pattern Recogniztion and Control </b><br /> 





# 📝 Publications 

<b> Journals </b>


- F. Han, and J. Yi, Safe Motion Control of Autonomous Vehicle Ski-Stunt Maneuvers. IEEE/ASME Trans. on Mechatronics, 2023. (*Under Review*)

- P. Wang, F. Han, and Yi, Jingang, "Gyroscopic Balancer-Enhanced Motion Control Of An Autonomous Bikebot," in Journal of Dynamic Systems, Measurement, and Control, pp. 1-15, 2023. <a href="https://asmedigitalcollection.asme.org/dynamicsystems/article/doi/10.1115/1.4063014/1164571"> Link</a>


- F. Han, X. Huang, Z. Wang, J. Yi and T. Liu, "Autonomous Bikebot Control for Crossing Obstacles With Assistive Leg Impulsive Actuation," in IEEE/ASME Transactions on Mechatronics, vol. 27, no. 4, pp. 1882-1890, Aug. 2022. <a href="https://ieeexplore.ieee.org/abstract/document/9781431/"> Link</a>

- F. Han, A. Jelvani, J. Yi and T. Liu, "Coordinated Pose Control of Mobile Manipulation With an Unstable Bikebot Platform," in IEEE/ASME Transactions on Mechatronics, vol. 27, no. 6, pp. 4550-4560, Dec. 2022. <a href="https://ieeexplore.ieee.org/abstract/document/9750394/"> Link</a>


- F. Han and J. Yi, "Stable Learning-Based Tracking Control of Underactuated Balance Robots," in *IEEE Robotics and Automation Letters*, vol. 6, no. 2, pp. 1543-1550, April 2021. <a href="https://ieeexplore.ieee.org/abstract/document/9345449/"> Link</a>


- T. Yigit, F. Han, E. Rankins, J. Yi, K. H. McKeever and K. Malinowski, "Wearable Inertial Sensor-Based Limb Lameness Detection and Pose Estimation for Horses," in IEEE Transactions on Automation Science and Engineering, vol. 19, no. 3, pp. 1365-1379, July 2022. <a href="https://ieeexplore.ieee.org/abstract/document/9743494"> Link</a>



<b> Conference </b><br /> 

- T. Zheng, F. Han, and J. Yi, Design and Control of An Agricultural Robot for Turf Grass Inspection. 2023 Modeling, Estimation and Control Conference. (*Accepted*)


- F. Han and J. Yi, "On the Learned Balance Manifold of Underactuated Balance Robots," *2023 IEEE International Conference on Robotics and Automation (ICRA)*, London, United Kingdom, 2023, pp. 12254-12260. <a href="https://ieeexplore.ieee.org/abstract/document/10161088/"> Link</a>

- F. Han and J. Yi, "Learning-based Safe Motion Control of Vehicle Ski-Stunt Maneuvers," 2022 IEEE/ASME International Conference on Advanced Intelligent Mechatronics (AIM), Sapporo, Japan, 2022, pp. 724-729. <a href="https://ieeexplore.ieee.org/abstract/document/9863309/"> Link</a>

- C. Deng, Y. Gong, F. Han, S. Liao, J. Yi and B. Yuan, "VLSI Hardware Architecture for Gaussian Process," *2020 54th Asilomar Conference on Signals, Systems, and Computers*, Pacific Grove, CA, USA, 2020, pp. 121-124. <a href="https://ieeexplore.ieee.org/abstract/document/9443272"> Link</a>



- X. Huang, F. Han, Y. Han, S. Wang, T. Liu and J. Yi, "Motion Control of an Autonomous Wheel-Leg Bikebot," 2022 IEEE 18th International Conference on Automation Science and Engineering (CASE), Mexico City, Mexico, 2022, pp. 2341-2346. <a href="https://ieeexplore.ieee.org/abstract/document/9926543/"> Link</a>


- T. Yigit, F. Han, E. Rankins, J. Yi, K. McKeever and K. Malinowski, "Wearable IMU-based Early Limb Lameness Detection for Horses using Multi-Layer Classifiers," 2020 IEEE 16th International Conference on Automation Science and Engineering (CASE), Hong Kong, China, 2020, pp. 955-960. <a href="https://ieeexplore.ieee.org/abstract/document/9216873"> Link</a>


- C. Zhu, F. Han and J. Yi, "Wearable Sensing and Knee Exoskeleton Control for Awkward Gaits Assistance," 2022 IEEE 18th International Conference on Automation Science and Engineering (CASE), Mexico City, Mexico, 2022, pp. 2393-2398. <a href="https://ieeexplore.ieee.org/abstract/document/9926655"> Link</a>

- M. Mihalec, F. Han, and J. Yi, "Integrated inverted pendulum and whole-body control design for bipedal robot with foot slip," IFAC-PapersOnLine,
Volume 55, Issue 37, pp. 376-381, 2022. <a href="https://www.sciencedirect.com/science/article/pii/S2405896322028555"> Link</a>



# Professional Avtivities

Reviewer for
- Journals: IEEE Trans. on Automation Science and Engineering, IEEE Trans. on Control Systems Technology, IEEE/ASME Trans. on Mechatronics, IEEE Robotics and Automation Letters, Control Engineering Practice, Mechatronics, Transportation Research Part C, International Journal of Intelligent Robotics and Applications, IEEE Transa. on Human-Machine Systems, 

- Conferences: American Control Conference (ACC), IEEE/ASME International Conference Advanced Intelligent Mechatronics (AIM), IEEE International Conference on Automation Science and Engineering (CASE), IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), IEEE International Conference on Intelligent Transportation Systems (ITSC), IEEE International Conference on Robotics and Automation (ICRA), IFAC