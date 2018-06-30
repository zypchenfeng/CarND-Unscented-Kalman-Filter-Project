The source code is in src folder

[//]: # (Image References)

[image1]: ./output_data/Laser_NIS.png "Laser NIS"
[image2]: ./output_data/Radar_NIS.png "Radar NIS"
[image3]: ./output_data/FinalResult.PNG "Final Result"

I did fine tune on `std_a_` and `std_yawdd_` base on the instruction from lecture.
```
std_a_ = 1.5; //car maximum acceleration is ~6m/s2, so bicycle about 1.5m/s2
std_yawdd_ = 0.5; //for bicycle to turn the direction of pi/4 needs about 1-2s
```
The final laser NIS can be seen in the first image

![alt text][image1]

The final radar NIS can be seen in the first image

![alt text][image2]

The final px, py, vx, vy is

![alt text][image3]
