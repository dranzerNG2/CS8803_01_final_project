# CS8803_01_final_project
Robot Path Prediction

- This repo contains project report for the final project done in course Georgia Tech's CS8803_01: Artificial intelligence for Robotics (http://omscs.gatech.edu/cs-8803-artificial-intelligence-robotics). 
- Adhering to guidelines laid down by University and Course Instructors, no Source Code has been shared. Only the final Project Report has been shared in this repo, which explains the challenges of the problem, approaches taken towards solving it and the accuracy results of such pproaches.

- Problem: A Real world Hexbug robot motion data, i.e. messy and noisy data, in a given fixed environment is provided.
- Our Task: Use any of the algorithms learnt in the course such as Kalman Filters, Particle Filters, SLAM or even outside the scope of course lectures to predict the motion of hexbug robot for the next 2 seconds(60 frames) given 30fps input data for 60s
- Techniques: Various statistical and non-statistical methods were considered, implemented and evaluated to find the method which provided the best accuracy results
- Results: KNN Regressor and Gradient Boosting provided the best results in our experiments where we were able to minimize an error metric based on the trajectory predictions obtained using these methods
