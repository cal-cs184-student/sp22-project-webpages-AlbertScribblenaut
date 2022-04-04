CS184 Project 3-2: Pathtracer
==============

***Due: April 1, 2022***

**Author:** *Albert Wen*

# Part 1

![CBspheres.dae with ray depth 0](images/part1/CBspheres-m0.png)

Figure 1: *CBspheres.dae with ray depth 0*

In Figure 1, when ray depth is 0, there is no illumination, so neither of the spheres is visible. Only the light from the ceiling is visible to the camera.

![CBspheres.dae with ray depth 1](images/part1/CBspheres-m1.png)

Figure 2: *CBspheres.dae with ray depth 1*

In Figure 2, the box surrounding the spheres is visible, but having a ray depth less than or equal to 1 results in solely direct illumination, therefore there is no reflection or refraction from the spheres. Shadows are accurately cast with ambient occlusion. One bounce enables the general shape of the spheres to be visible to the pin-hole camera.

![CBspheres.dae with ray depth 2](images/part1/CBspheres-m2.png)

Figure 3: *CBspheres.dae with ray depth 2*

Figure 3 shows reflection from both spheres, which is expected for at least the left sphere. However, the right sphere is dark because it is intended to refract light. Without a larger ray depth, there is no total internal reflection.

![CBspheres.dae with ray depth 3](images/part1/CBspheres-m3.png)

Figure 4: *CBspheres.dae with ray depth 3*

As seen in Figure 4, the right sphere is now properly illuminated and refracts light, resulting in a glowing ellipse on the floor.

![CBspheres.dae with ray depth 4](images/part1/CBspheres-m4.png)

Figure 5: *CBspheres.dae with ray depth 4*

With an additional

![CBspheres.dae with ray depth 5](images/part1/CBspheres-m5.png)

Figure 6: *CBspheres.dae with ray depth 5*


![CBspheres.dae with ray depth 100](images/part1/CBspheres-m100.png)

Figure 7: *CBspheres.dae with ray depth 100*


* Point out the new multibounce effects that appear in each image.
* Explain how these bounce numbers relate to the particular effects that appear.

# Part 4
* In a few sentences, explain the differences between a pinhole camera model and a thin-lens camera model.

![CBdragon.dae with aperture 1.23, depth 4.56](images/part4/CBdragon/CBdragon-b1.23-d4.56.png)
*

## Focus stack with aperture change, depth at 4.56
![CBdragon.dae with aperture 0.25](images/part4/CBdragon/aperture_change/CBdragon-b0.25-d4.56.png)

![CBdragon.dae with aperture 0.5](images/part4/CBdragon/aperture_change/CBdragon-b0.5-d4.56.png)

![CBdragon.dae with aperture 0.75](images/part4/CBdragon/aperture_change/CBdragon-b0.75-d4.56.png)

![CBdragon.dae with aperture 1](images/part4/CBdragon/aperture_change/CBdragon-b1-d4.56.png)

## Focus stack with depth change, aperture at 1.23

![CBdragon.dae with depth 1](images/part4/CBdragon/depth_change/CBdragon-b1.23-d1.png)

![CBdragon.dae with depth 2](images/part4/CBdragon/depth_change/CBdragon-b1.23-d2.png)

![CBdragon.dae with depth 3.75](images/part4/CBdragon/depth_change/CBdragon-b1.23-d3.75.png)

![CBdragon.dae with depth 4](images/part4/CBdragon/depth_change/CBdragon-b1.23-d4.png)




# Web Page
[Written in Markdown, hosted on GitHub](https://github.com/cal-cs184-student/sp22-project-webpages-AlbertScribblenaut/edit/master/proj3-2/index.md)
