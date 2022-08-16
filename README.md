# Localization in ROS with Unscented Kalman Filter

## Description

Sensor fusion is achieved by combining odometry data and laser data via Unscented Kalman Filter (UKF).
The laser data is matched against a map which was created offline to receive an estimated location via the usage of the iteration closest point algorithm.

The covarianz matrix was estimated empirically.   
