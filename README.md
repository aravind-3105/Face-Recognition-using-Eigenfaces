# SMAI-Family-Project

# Face Recognition using Eigenfaces
##  TEAM MEMBERS:

- Aravind Narayanan - 2019102014

- Abhayram A Nair  - 2019102017

- Vaibhav Bhushan - 2019112019

- Rishin Chakraborty - 2019112008

#  Goal of the project:

The primary goal of this project was to implement the method of Eigenfaces for face recognition by projecting the face images on the feature space (face space) which best represents the variations among distinct faces. We also implement Fischerfaces. This was done using Linear Discriminant Analysis. We have also compared the results of these two algorithms with another well-known method (LBPH).  

#  Setting up the code:
#### To view the step-by-step functioning of the segmenation:
  
View : [RetinalSegmentation.ipynb](https://github.com/Digital-Image-Processing-IIITH/dip-project-society/blob/main/RetinalSegmentation.ipynb "RetinalSegmentation.ipynb")

#  Repository Structure
#### Folders:
All the data required are present in the repository, however if required they can be downloaded from here as well [DATA](https://iiitaphyd-my.sharepoint.com/personal/abhayram_a_students_iiit_ac_in/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fabhayram%5Fa%5Fstudents%5Fiiit%5Fac%5Fin%2FDocuments%2FDIP%20Project "DATA")
1. [dataset](https://github.com/Digital-Image-Processing-IIITH/dip-project-society/tree/main/dataset "dataset"): 20 input images used for testing the code
2. [results](https://github.com/Digital-Image-Processing-IIITH/dip-project-society/tree/main/results "results"): 20 output images of the respeciive inputs
3. [testing/labels-ah](https://github.com/Digital-Image-Processing-IIITH/dip-project-society/tree/main/testing/labels-ah "This path skips through empty directories") : 20 ground truth images used for performance analysis
4. resource: contains images used for readme file
5. requirements.txt: Contains list of dependencies(extra dependencies needed to view in jupyter lab are also added)
6. retinalSeg.py: python script version of entire algorithm
7. script.py: GUI implementation
8. RetinalSegmenation.ipynb: Jupyter notebook implementation of algorithm

Link to [presentation](https://github.com/Digital-Image-Processing-IIITH/dip-project-society/blob/main/DIP%20PROJECT%20-%20Society.pptx "presentation"). Link to [presentation pdf](https://github.com/Digital-Image-Processing-IIITH/dip-project-society/blob/main/DIP%20PROJECT%20-%20Society.pdf "presentation pdf")

# Dataset
Two different datasets have been used to obtain the face images
- the AT&T dataset: [Link](https://www.kaggle.com/kasikrit/att-database-of-faces)
- the Yale B dataset: [Link](http://vision.ucsd.edu/~iskwak/ExtYaleDatabase/ExtYaleB.html)

Preprocessing has been done on the Yale B dataset for more accurate results
