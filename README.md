# toolClustering_dataset

Note: tools.tar.gz contains everything related to this dataset.

### 1. TITLE: 

      Tool Database for image-set clustering

### 2. CONTACT: 

      Joris GUERIN
      Laboratoire des Sciences de l'Information et des Systèmes (INSM team)
      Ecole Nationale supérieure des Arts et Métiers
      8 Boulevard Louis XIV
      59800 LILLE
      FRANCE
      Tel. (+33) 783699592
      email: joris.guerin@ensam.eu // joris.guerin.110@gmail.com

### 3. RELEVANT INFORMATION:
      
This database was generated to evaluate a robotic application dealing with 
image-set clustering. The goal is to sort and store tools on an table in an
unsupervised way, from pixel inputs. Pictures contains objects that can be 
found in a shopfloor. Each picture contains only one object. There are five
different conditions, for each condition, lighting conditions and background 
are changed. For each condition, four picture of each object are taken under
different orientations.

### 5. NUMBER OF INSTANCES:

5 lighting and background conditions
7 types of objects per condition
3 to 6 objects per class
4 image per object

560 images in total

### 6. NUMBER OF CLASSES:

This dataset can be used for object grouping (7 classes), as well as fine-grained classification (# of classes = # of object per group.)

### 7. NAMING CONVENTION:

Each lighting and background setups are grouped in different folders (conditioni).
In each condition folder, pictures of different objects are grouped in subfolders representing classes.
In each subfloder, images are named "ij.jpg", where i is the object, and j the picture number.
All pictures "ij.jpg" belonging to the same subfolder represent the same object i (whatever j is).

### 8. MISSING ATTRIBUTE VALUES: 

None

### 9. CITATION:

If you find this dataset useful in your research, please consider citing:

      @article{guerin2017cnn,
        title={CNN features are also great at unsupervised classification},
        author={Gu{\'e}rin, Joris and Gibaru, Olivier and Thiery, St{\'e}phane and Nyiri, Eric},
        journal={arXiv preprint arXiv:1707.01700},
        year={2017}}
