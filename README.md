# computer_vision_object_identify_tracking

There are several objects that have different colors,
moving by straight-line or curve trails.
The task is to find their moving trails, 
and find the one (or ones) whose trail(s) is/are curve，
as well as their distances from the stereo cameras.

The stereo cameras that include left and right cameras, just like human's left and right eyes,
have recorded those moving objects by left and right frames (in the left and right folders).
For the stereo cameras, focal length: 12m, baseline (distance between the two cameras): 3500m, and the pixel of frame is 10^-5m (0.00001m).

有几个运动的物体，它们是不同的颜色，有的直线运动，有的曲线运动。
目的是，识别这些物体，并找出它们运行的轨迹，直线还是曲线。

用双目相机，包含左相机和右相机，类似于人的双眼，这样的话可以对比计算出深度，也就是物体到相机的距离。
物体运动的过程，记录在了两个文件夹里面，一共是50帧。
双目相机，
焦距：12米，
左右相机的距离：3500m，
像素点的大小为：10E-5m。

