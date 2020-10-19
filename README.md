# social_distance_detector

This project used YOLO object detection algorithm to detect people in a video and use eucledian distance geometry to calculate the distance between them and compares this distance against a set allowable distance between people. Distance between people that violates this minimum distance are classified as violating the social distance rule.



![alt text](https://github.com/jimohafeezco/social_distance_detector/blob/master/dist_detector.gif)


#Limitation

The ideal detector should do camera calibration to actually help in calculating the distance betweeen people because currently now, if video is recorded from afar distance, the distance between people appears to be close which might not be true. But with camera calibration and distance between video frame and camera, the detector algorithm can be improved
