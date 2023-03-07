# Autonomous_Driving_Navigation_Map
Application of computer vision for autonomous driving using YOLO_V3 and OpenCV.

## video file is renamed...

Using Yolo V3 and Open CV, a live navigation map is created from dashcam feed as input.

Already trained yellow V3 weights configuration and labels files have been used.

the yolo is detecting objects which in this case are cars.It can also detect pedestrians.


On the navigation map, cars can be seen on their respective lanes and at scale distance.

We can also see some cars on other side of the road being detected and appearing on the navigation map, but they are not relevant for navigation in this case.

In case there is no divider in between, the vehicles will be detected properly and appear on correct position on the navigation map.

The Yolo model used has 80 classes for detection and most of those are not relevant for autonomous driving.The model can be modified or a new model can be created with only the relevant objects.Which can then be trained and applied for high FPS processing.
