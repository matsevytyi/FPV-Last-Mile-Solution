# FPV Drone Last Mile Solution

Nowadays battlefield is rapidly changing. Being an unexpectedly powerful tool in 2022-2023, fpv-kamikaze drones started loosing their efficectiveness, being countered by electronic warfare devices.
This issue is called "Last Mile Problem", because these countermeasures work on relatively small distance, making it still impossible to strike the target manually. 

One of its main solution approaches is distribution of responsibility between human operator and the machine. In particular, operator leads the drone, manually locates the target once there is a visual access to it, and drone continues following it automatically.

My solution implements Channel-Spacial Reliability and MedianFlow tracking techniques and can be installed using Python or C++. As output it provides reflection on object position change that is interpreted to flight controller commands. 

I increased model sperformance on RaspPi3b from 3 to 11 FPS by fine-tuning algorithm parameters and applying NEON and VFPv4 acceleration. For known reasons I can't publish the code of the system, nevertheless, below you may see a video of its flight tests on 7" quadracopter with betaflight controller



https://github.com/user-attachments/assets/764dd074-e68f-40b4-b5db-b15a82a582ce

