# SMAI-Family-Project

# Face Recognition using Eigenfaces
##  TEAM MEMBERS:

- Aravind Narayanan - 2019102014

- Abhayram A Nair  - 2019102017

- Vaibhav Bhushan - 2019112019

- Rishin Chakraborty - 2019112008

#  Goal of the project:

The primary goal of this project was to implement the method of Eigenfaces for face recognition by projecting the face images on the feature space (face space) which best represents the variations among distinct faces. We also implement Fischerfaces. This was done using Linear Discriminant Analysis. We have also compared the results of these two algorithms with another well-known method (LBPH).  

#  Repository Structure
#### Folders:
All the data required are present in the repository, however if required they can be downloaded links mentioned in the dataset section of README
1. [dataset](https://github.com/aravind-3105/SMAI-Family-Project/tree/main/final_dataset): Contains 4 folders i) at&t dataset ii)yaleB dataset iii)miscellaneous folder used for comparison iv) PinDown__faces-of-everyday-objects contains no-face images which gives appearance of face
2. [YaleB](https://github.com/aravind-3105/SMAI-Family-Project/blob/main/YaleB.ipynb): Contains entire implementation of eigenfaces on YaleB dataset along with test images classification
3. [AT&T](https://github.com/aravind-3105/SMAI-Family-Project/blob/main/AT_T.ipynb): Contains entire implementation of eigenfaces on AT&T dataset along with test images classification
4. [fischer](https://github.com/aravind-3105/SMAI-Family-Project/blob/main/fischerfaces.ipynb): Contains entire implementation of fischerfaces on YaleB dataset along with test images classification
5. [comparison](https://github.com/aravind-3105/SMAI-Family-Project/blob/main/comparison.ipynb): Contains testing of eigenfaces by training on YaleB and testing for non-face images and mixiture of face,non-face images
6. [LBPH](https://github.com/aravind-3105/SMAI-Family-Project/blob/main/LBPH.ipynb): Contains testing of alternate method used from reference directly purely for comparison purpose
7. [InbuiltEigen](https://github.com/aravind-3105/SMAI-Family-Project/blob/main/Inbuilt_Eigenfaces.ipynb): Using an inbuilt function on yaleB dataset to check for accuracy comparison

# Dataset
Two different datasets have been used to obtain the face images
- the AT&T dataset: [Link](https://www.kaggle.com/kasikrit/att-database-of-faces)
- the Yale B dataset: [Link](http://vision.ucsd.edu/~iskwak/ExtYaleDatabase/ExtYaleB.html)
- No-Face dataset: A dataset of images without faces, sourced from pinterest. Uploaded in the Repository
- Additional miscellaneous images obtained from google
NOTE: All of them are available in the github repository itself.<br>
Preprocessing has been done on the Yale B dataset for more accurate results.

#### NOTE: ALL CODES ARE IN JUPYTER NOTEBOOK AND DATASET AND IN THE REPOSITORY ITSELF
