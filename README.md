# Individual-project
**Note: The group woek has not been finished completely yet, everyone maybe add some ditails to perfect the work,
so I started parts of my individual work based on the progress of the group work to ensure I can submit on time.
Eventually, my individual task will contain the completed group project coding**



**My individual task: Time-Based and Events**

Details of my individual approach:(comments have further details):

1. The dotted line circles are **rotating** based on stepInterval and function autoClock()

- Technical explanation:
  - The ratations with 4 layers of dottedline circles by *setInterval()* taught in tutorial 5, and each layer rotates at different speed.
  I initialized the rotating angles and calling speed:
*let rotAngles = [0, 0, 0, 0];
let stepInterval = 100;*

  - A function to differ speed in 4 layers:
*function autoClock(){
  rotAngles[0] += 0.01;
  rotAngles[1] += 0.02;
  rotAngles[2] += 0.015;
  rotAngles[3] += 0.025;
}*
Rotating each layer by *rotate()* in the nested for-loop, so every layer matches *rotAngles[i]*
![alt text](image.png)


