
# Final Project Code

## About The Project 

The goal of this project was to determine whether you could classify fabrics based on their content makeup with images alone. This project utilizes a data set of 6 different fabric groups and 15 different fabric contents. The dataset is uploaded to Canvas and is an h5 file. The data set is called "data_h5". The main code file is called Fabric_Content_LBP_GLCM. This file utilizes LBP and GLCM texture features to classify images based on their content. Three different classifier results are reported (SVM, Logistic Regression, and KNN). For more information about this project see  the paper "Fabric Content Classification Using Textural Properties." 

## Getting Started 

### Dependencies

* sklearn
  ```sh
  conda install -c conda-forge scikit-learn
    ```
* scikit-image 
  ```sh
  conda install scikit-image
  ```
* Keras-preprocessing 1.1.2 
  ```sh
  pip install Keras-Preprocessing
  ```
* h5py 
  ```sh
  conda install h5py
  ```
  
### Alternative: Export your Environment
  
  ```sh
  conda env export > environment.yml
  ```

recreate environment using:

  ```sh
  conda env create -f environment.yml
  ```
  
### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/uf-eel6825-sp23/final-project-code-catalinamurray.git
   ```
2. Setup (and activate) your environment
   ```sh
        conda env create -f enviornment.yml
   ```


## Usage

1. Download the data file named "data_h5". 
2. Run the file labeled "Fabric_Content_LBP_GLCM". 

Note* There are some extra files, for example, the file named "fabric_all_classes" runs the same code for all the classes grouped together. The file named "fabric_clustering" uses the same features for clustering methods. These files were not apart of the proposed method but I included results from them in the paper and in the video presentation so I decided to include them in the repository as well. 


 ## License

Distributed under the MIT License. See `LICENSE` for more information.


 ## Authors

Catalina Murray, catalinamurray@ufl.edu 

Project Link: [https://github.com/uf-eel6825-sp23/final-project-code-catalinamurray](https://github.com/uf-eel6825-sp23/final-project-code-catalinamurray)


 ## Acknowledgements

This code was developed as a part of the final project for the Pattern Recognition class at the University of Florida. The methods utilized are based on methods found in a number of articles including the citations listed below. 

* Tsai, I-Shou, Chung-Hua Lin, and Jeng-Jong Lin. "Applying an artificial  neural network to pattern recognition in fabric defects." Textile Research  Journal 65, no. 3 (1995): 123-130. 
* Zhang, Jie, Binjie Xin, and Xiangji Wu. "A review of fabric identification  based on image analysis technology." Textiles and Light Industrial  Science and Technology 2, no. 3 (2013): 120-130. 
* Sun, Xudong, Mingxing Zhou, and Yize Sun. "Classification of textile  fabrics by use of spectroscopy-based pattern recognition  methods." Spectroscopy Letters 49, no. 2 (2016): 96-102. 
* Kampouris, Christos, et al. "Fine-grained material classification using  micro-geometry and reflectance." Computer Vision–ECCV 2016: 14th  European Conference, Amsterdam, The Netherlands, October 11-14,  2016, Proceedings, Part V 14. Springer International Publishing, 2016. 
* Rasheed, Aqsa, et al. "Fabric defect detection using computer vision  techniques: a comprehensive review." Mathematical Problems in  Engineering 2020 (2020): 1-24. 
* Zhang, Wuyi, et al. "MWGR: A new method for real-time detection of  
* Iqbal Hussain, Muhammad Ather, et al. "Woven fabric pattern recognition  and classification based on deep convolutional neural  networks." Electronics 9.6 (2020): 1048. 
* “Tf.keras.preprocessing.image.imagedatagenerator : Tensorflow  V2.12.0.” TensorFlow,  https://www.tensorflow.org/api_docs/python/tf/keras/preprocessing/ima ge/ImageDataGenerator.  
* “Sklearn.linear_model.Logisticregression.” Scikit, https://scikit learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegres sion.html.  
* “Sklearn.linear_model.Logisticregression.” Scikit, https://scikit learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegres sion.html.  
*  “Sklearn.neighbors.kneighborsclassifier.” Scikit, https://scikit learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassi fier.html. 


### Thank you

