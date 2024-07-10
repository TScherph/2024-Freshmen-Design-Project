# Freshmen Design Class - Dynamic Functioning Arm

In the spring of my freshmen year as a mechanical engineering student, 2024, I took a 10 week course called "Freshmen Design" where my section of the course was tasked with creating a medical device or invention that could be easily produced and created to help those who needed it. I was put into a group of 5 total members, and after some discussion we decided that we would create a modular prosthetic arm. 

Our projects goal was to, from scratch, develop a robotic arm that was capable of seperating into each of its important components, each self sufficient, and to be able to reassemble this in a multiutude of fashions, We argued that if a prosthesis using this design were developed, it would be advantagous as you could have different attachments for different purposes. A more rigid or solid hand or fingers for tasks like lifting heavy objects, but a more flexible and softer hand for more intricate tasks like holding glasses or reading a book. The beauty of our project was that the interchangability of these parts would all come down to 3 things. A simple 3d printed design with a magnetic clasp, an independant bluetooth microcontroller on each part, and compact simple wiring. 
We achieved this by using self made wire bundles, esp32 modules that were programmed to listen to a central controller located off of the arm, and a 3dprinted design of a clip and magnets.

My role in this project was the CAD, rendering, and assembly of the arm. I assisted in the programming of some motor controlling and bluetooth, but the programming of the gyroscope and its calculations, along with the more effectient motor control was left to two other members. 

Throughout the 10 week course, though we had to present the finished project at the end of the 9th week, I went through 2 major designs both shown below.

![IMG_2058](https://github.com/TScherph/College-Arm-/assets/147080935/6888c605-a0aa-49fc-bc5c-4d6117e7348e)

![image](https://github.com/TScherph/College-Arm-/assets/147080935/10abb577-1513-47fe-930f-80ef4a5a5745)


The first design shown features a 20x20 aluminum extrusion as the base for most of the arm, this was before we really focused on the modularity aspect of the project, the fingers freatured also use a screw and nut based linear actuator design using small N20 motors with M3 screws and nuts that drives a linkage allowing the finger to curl. We found a major issue with this design is that it was much too rigid for a project that required as much movement as this did. So I ended up changing it to a tension based design shown in the second photo. This design used the same N20 Motors to pull a cord of fishing line attached inside and at the top of each finger to fight against rubberbands on the back to get the curling motion, when the motor unwound the tension would bring the fingers to the open position. 

This project was presented at the Drexel University Celebration of Engineering Design 2024 competition and we were awarded second place for the freshmen category.
