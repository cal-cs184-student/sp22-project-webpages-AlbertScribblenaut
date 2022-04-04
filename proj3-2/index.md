CS184 Project 3-2: Pathtracer
==============

***Due: April 1, 2022***

**Author:** *Albert Wen*

# Part 1
* Show a sequence of six images of scene CBspheres.dae rendered with max_ray_depth set to 0, 1, 2, 3, 4, 5, and 100. The other settings should be at least 64 samples per pixel and 4 samples per light.

![CBspheres.dae with ray depth 0](images/part1/CBspheres-m0.png)

![CBspheres.dae with ray depth 1](images/part1/CBspheres-m1.png)

![CBspheres.dae with ray depth 2](images/part1/CBspheres-m2.png)

![CBspheres.dae with ray depth 3](images/part1/CBspheres-m3.png)

![CBspheres.dae with ray depth 4](images/part1/CBspheres-m4.png)

![CBspheres.dae with ray depth 5](images/part1/CBspheres-m5.png)

![CBspheres.dae with ray depth 100](images/part1/CBspheres-m100.png)

* Point out the new multibounce effects that appear in each image.
* Explain how these bounce numbers relate to the particular effects that appear.

# Part 4
![CBdragon.dae with aperture 1.23, depth 4.56](images/part4/CBdragon/CBdragon-b1.23-d5.46.png)

## Focus stack with aperture change, depth at 4.56
![CBdragon.dae with aperture 0](images/part4/CBdragon/aperture_change/CBdragon-b0-d4.56.png)

![CBdragon.dae with aperture 0.02](images/part4/CBdragon/aperture_change/CBdragon-b0.02-d4.56.png)

![CBdragon.dae with aperture 1.02](images/part4/CBdragon/aperture_change/CBdragon-b1.02-d4.56.png)

![CBdragon.dae with aperture 1.15](images/part4/CBdragon/aperture_change/CBdragon-b1.15-d4.56.png)

## Focus stack with depth change, aperture at 1.23

![CBdragon.dae with depth 1](images/part4/CBdragon/depth_change/CBdragon-b1.23-d1.png)

![CBdragon.dae with depth 2](images/part4/CBdragon/depth_change/CBdragon-b1.23-d2.png)

![CBdragon.dae with depth 3.75](images/part4/CBdragon/depth_change/CBdragon-b1.23-d3.75.png)

![CBdragon.dae with depth 4](images/part4/CBdragon/depth_change/CBdragon-b1.23-d4.png)

* In a few sentences, explain the differences between a pinhole camera model and a thin-lens camera model.
* Show a "focus stack" where you focus at 4 visibly different depths through a scene.
* Show a sequence of 4 pictures with visibly different aperture sizes, all focused at the same point in a scene.



# Web Page
[Written in Markdown, hosted on GitHub](https://github.com/cal-cs184-student/sp22-project-webpages-AlbertScribblenaut/edit/master/proj3-2/index.md)
