# ADORESet
 Annotated Desktop Objects Real and Ersatz Images Dataset
 
  A Hybrid Image Dataset Towards Bridging The Gap Between Real And Simulation Environments For Robotics

This project includes an annotation tool for images called ITurk GUI, which enables users to tag the objects within images with successor objects and links for the dataset. ITurk GUI also allows to specify the pixel-wise limits of the objects you annotate.

After you install and run the ITurk GUI codes by arranging the necessary paths, you can process 24 images at a time until the images to be processed are finished in the folder you retrieve the images.

Please cite us:

Bayraktar, E., Yigit, C., B., Boyraz, P. (2018). A hybrid image dataset toward bridging the gap between real and simulation environments for robotics, Machine Vision and Applications, https://doi.org/10.1007/s00138-018-0966-3.

@article{bayraktar2018a,
  title={A hybrid image dataset toward bridging the gap between real and simulation environments for robotics},
  author={Bayraktar, Ertugrul and Yigit, Cihat Bora and Boyraz, Pinar},
  journal={Machine Vision and Applications},
  doi={https://doi.org/10.1007/s00138-018-0966-3},
  year={2018},
  publisher={Springer-Verlag GmbH Germany}
}

Link to the paper: 
 https://link.springer.com/epdf/10.1007/s00138-018-0966-3?author_access_token=2aYSdv2UbdplcVwxeYfTTve4RwlQNchNByi7wbcMAY6tH0b12ZbLNO2xbmENW5Q8jnWq9P5HfxELXvWjj73UVNrJ1hkaqISWi1ICet1vMP2sGHaIFaEx4mr30oJtLRUsxijFYyt0V2G106vUNbTSyw%3D%3D

In most cases, machine vision based problems in robotics such as object detection and recognition, object tracking and manipulation are performed using real-world or simulation images, separately. In addition, these images routinely belong to the categories of objects namely tableware, glassware and similar kinds of objects, which may exist on desktops, in the form of relatively small, graspable, pushable states. In consideration of the primary purpose of robotics applications in the field of computer vision and control in terms of imitating humans or obtaining even better results, inclusion of irrelevant object classes in image datasets for instance wild animals, large structures, big vehicles, etc. is infeasible which cause worse performance results. Moreover, time spent during developments in robotics is another variable aimed to be reduced, which restricts maneuverability and diversity. In order to optimize this period, the referred method is to utilize simulation environments, which replicate real-world conditions as much as possible. However, simulation experiments of robotics applications give successful results; the outcomes cannot be directly used in real-world experiments or end-user products by means of inconsistencies between real and simulation environments. In consequence, we propose annotated desktop objects real and ersatz images dataset (ADORESet) that is able to accomplish these issues with its compact form, which provides purposeful object categories with sufficient number of real and synthetic images. 

Link for Real Images: https://kovan.itu.edu.tr/index.php/s/CN4vqI8gfedmCHe

Link for Synthetic Images: https://kovan.itu.edu.tr/index.php/s/yOv9vfxcorTSG9S

ADORESeT is composed of colored images, which has 30 classes with the dimension of 300x300 pixels. Each class has 2500 real-world images acquired from wild web and 750 synthetic images that are generated within Gazebo Simulation Environment (GSE). All images are stored in JPEG format. There are 97500 images that take up about 1.8 GB space in the hard drive which makes it simpler to achieve than ImageNet (1.2 million images for 1000 classes) and MS COCO (300.000 images for 80 classes). Although, our dataset has less total images than these two datasets, it includes more labeled instances per category.

This hybrid dataset enables researchers to implement their algorithms both for real-world and simulation environment conditions. Our hybrid dataset is fully-annotated and the limits of objects are manually specified and bounding box coordinates are provided. Successor objects are also labeled to give statistical information about the relations of the objects within dataset. For example, the relation between monitor, keyboard and mouse can be directly obtained using this useful information. ADORESet should be of interest to field of robotics researchers by means of its hybrid form, compactness in terms of lightweight and relevancy to robotics applications such as detection and recognition, grasping and dexterous manipulation of objects.
