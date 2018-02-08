# Distraction-Recognition-of-a-Driver

Busy life as well as prevalence of infotainment is increasingly making people more occupied even during tasks that require serious attention. One such task is driving and at the same time getting involved in activities that may distract them cognitively from watching the road and cause fatal accidents. This work presents a method that is capable of monitoring different types of distractions such as talking and texting on cell phone, casual eating and operating cabin equipment while driving, so that a driver can be assisted to remain cautious on road. The proposed method automatically detects and tracks fiducial body parts of a driver from video captured by a camera mounted on the front windshield inside a vehicle. Relative distances between the tracking trajectories are used as features that represent
actions of the driver. Then, the well-known kernel support vector machine is applied for recognizing a particular distraction from the features extracted from body parts. The proposed feature is also compared with previously employed features for tracking-based human action recognition schemes to substantiate its better result in terms of mean accuracy and robustness for distraction recognition. The effectiveness of the proposed method of distraction recognition is also analyzed with respect to tracking errors.

# Research Paper

Please see our initial results published [here](http://ieeexplore.ieee.org/document/7738077/) in 13 IEEE AVSS, Colorado Springs, Colorado

# Real Time Tracking Videos

<p align="center">
  <img src="https://github.com/tashrifbillah/Distraction-Recognition-of-a-Driver/blob/master/Tracking_Figure.png">
</p>

The videos in this repository demonstrate real-time and simultaneous tracking of three body parts- hand, lips, and forehead for the following instances. It also shows the evolution of trajectory-based features i.e. hand-lips distance and hand-forehead distance, as tracking progresses over time. Challenging scenarios such as- illumination variation, out of the frame hand movement, road bumping are shown in the video to corroborate robustness of our algorithm. In particular, the tracking videos depict the following actions-

1. [Driving attentively](https://github.com/tashrifbillah/Distraction-Recognition-of-a-Driver/blob/master/Attentive_high_res.mp4)
2. [Eating snacks while driving](https://github.com/tashrifbillah/Distraction-Recognition-of-a-Driver/blob/master/Eating_high_res.mp4)
3. [Talking on cell phone during driving](https://github.com/tashrifbillah/Distraction-Recognition-of-a-Driver/blob/master/Cell_phone_high_res.mp4)
4. [Texting while driving](https://github.com/tashrifbillah/Distraction-Recognition-of-a-Driver/blob/master/Texting_high_res.mp4)
5. [Operating cabin equipment during driving](https://github.com/tashrifbillah/Distraction-Recognition-of-a-Driver/blob/master/Inattentive_high_res.mp4)


# Database Description

Please see the research description and database download link [here](http://teacher.buet.ac.bd/mahbubur/resources/ebdd_database.htm).

If you use our database, please cite our paper as follows-

T. Billah and S. M. Mahbubur Rahman, "Tracking-based detection of driving distraction from vehicular interior video," 2016 13th IEEE International Conference on Advanced Video and Signal Based Surveillance (AVSS), Colorado Springs, CO, 2016, pp. 423-428.
doi: 10.1109/AVSS.2016.7738077

@INPROCEEDINGS{7738077, 
author={T. Billah and S. M. Mahbubur Rahman}, 
booktitle={2016 13th IEEE International Conference on Advanced Video and Signal Based Surveillance (AVSS)}, 
title={Tracking-based detection of driving distraction from vehicular interior video}, 
year={2016}, 
volume={}, 
number={}, 
pages={423-428}, 
keywords={feature extraction;image capture;image classification;image motion analysis;road safety;video cameras;video signal processing;Euclidean distance;K-nearest neighbor classifier;driver attention;driver body part tracking;driver distraction;feature extraction;front camera;global road safety;tracking-based driving distraction detection;tracking-based human action identification;vehicular interior video capture;Cellular phones;Feature extraction;Forehead;Lips;Tracking;Trajectory;Vehicles}, 
doi={10.1109/AVSS.2016.7738077}, 
ISSN={}, 
month={Aug},}
