CS184 Project 3-2: Pathtracer
==============

***Due: April 1, 2022***

**Author:** *Albert Wen*

# Part 1
* Show a sequence of six images of scene CBspheres.dae rendered with max_ray_depth set to 0, 1, 2, 3, 4, 5, and 100. The other settings should be at least 64 samples per pixel and 4 samples per light.

![CBspheres.dae with ray depth 0](images/part1/CBspheres-m0.png)
*CBspheres.dae with ray depth = 0*

![CBspheres.dae with ray depth 1](images/part1/CBspheres-m1.png)

![CBspheres.dae with ray depth 2](images/part1/CBspheres-m2.png)

![CBspheres.dae with ray depth 3](images/part1/CBspheres-m3.png)

![CBspheres.dae with ray depth 4](images/part1/CBspheres-m4.png)

![CBspheres.dae with ray depth 5](images/part1/CBspheres-m5.png)

![CBspheres.dae with ray depth 100](images/part1/CBspheres-m100.png)

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
