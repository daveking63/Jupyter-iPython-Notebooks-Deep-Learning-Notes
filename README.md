# Jupyter-iPython-Notebooks-Deep-Learning-Notes
Summary bibliography and notes from a variety of recent book chapters and articles dealing with Deep Learning, TensorFlow and Keras.

(In process)

This summary focuses on various introductory bibliographical sources (book chapters, articles, tutorials, and iPython notebooks) focused on "getting started" with understanding, building, testing and training deep learning models using primarily TensorFlow and Keras. When possible, each source details access to existing iPython notebooks that can be executed on either Jupyter.org's <a href="https://nbviewer.jupyter.org/">nbviewer</a> or <a href="https://colab.research.google.com/notebooks/intro.ipynb">Google's Colab</a>. Additionally, and primarily for my own edification, I've also provided access to my own notes for selected parts of the sources. These notes can also be view on either nbviewer or Colab. 

This summary contains bibliographical sources, pointers to existing code (including iPython .ipynb> notebooks), and notes that I've created using either iPython or <a href="https://colab.research.google.com/notebooks/intro.ipynb">Google's Colab</a>.  

<h3>Sources</h3>

<ul>
    <li>Source: <a href="https://www.packtpub.com/big-data-and-business-intelligence/predictive-analytics-tensorflow">Predictive Analytics with TensorFlow.</a> Md. Rezaul Karim, Packt Publishing, 2017.
    <ul>
    <li>Code: https://github.com/PacktPublishing/Mastering-Predictive-Analytics-with-scikit-learn-and-TensorFlow.</li>
    <li>Personal Notes: Chapter 3 (From Data to Decisions: Getting Started with TensorFlow) and Chapter 7 (Using Deep Neural Networks for Predictive Analytics). Chapter 7 analyzes 'bank telemarketing' data for predicting client subscription to telemarketing programs based on 21 demographic and marketing attributes for 41K clients. See: https://nbviewer.jupyter.org/github/daveking63/Jupyter-iPython-Notebooks-Deep-Learning-Notes/blob/master/notes_predictive_analytics_with_tensorflow-ch-3-7.ipynb</li>
    </ul>
    </li> 
<br>  
    <li>Source: <a href="https://www.packtpub.com/big-data-and-business-intelligence/mastering-predictive-analytics-scikit-learn-and-tensorflow">Mastering Predictive Analytics with scikit-learn and TensorFlow.</a> Alan Fontaine. Packt Publishing, 2018.
    <ul>
    <li>Code: The original code and notebooks can be found at https://github.com/PacktPublishing/Mastering-Predictive-Analytics-with-scikit-learn-and-TensorFlow.</li>
    <li>Personal Notes: Chapters 4 (Introduction to Artificial Neural Networks and TensorFlow) and 5 (Predictive Analytics with TensorFlow and Deep Neural Networks). Chapter 5 focuses on the MNIST handwritten digits dataset with 60K training and 10K testing images each with 28x28 = 728 pixels (features). See: https://nbviewer.jupyter.org/github/daveking63/Jupyter-iPython-Notebooks-Deep-Learning-Notes/blob/master/notes_from_mastering_predictive_analytics_Ch4-5-Manning.ipynb</li>
    </ul>
    </li>
<br>
     <li>Source: <a href="https://www.manning.com/books/deep-learning-with-python-second-edition">Deep Learning with Python 2nd Edition.</a> Francois Chollet, Manning Publication, 2020 (currently in MEAP or draft form).
    <ul>
    <li>Code: From first edition is at https://github.com/fchollet/deep-learning-with-python-notebooks</li>
    <li>Personal Notes: Chapter 3 (Introduction to Keras and TensorFlow) and 4 (Getting Started with Neural Networks: Classification and Regression). Chapter 4 covers 3 datasets: IMDB set of 50K polarized movie reviews for predicting overall positive vs. negative reviews using the text content of the review; Reuters set of 8982 training and 2246 testing newswires for determining which of 46 topics best describes overall content; a regression example predicting median price of homes in given Boston suburb in mid-1970s for 506 training and 102 test samples each with 13 numerical features. The notes for these chapters -- 'DLPython2ndCh3.ipynb' and 'DLPython2ndCh4.ipynb' -- are provided in this repository and were originally created in Google's Colab. Simply click on notebook name in the file listing above and you'll be provided access to Colab.</li>
     </ul>
     </li>
<br>
     <li>Source: <a href="https://www.tensorflow.org/tutorials/keras/classification">TensorFlow: Basic Classification - Classifying Images of Clothing.</a>
    <ul>
    <li>Code:at https://github.com/tensorflow/docs/blob/master/site/en/tutorials/keras/classification.ipynb. Enables running of the tutorial either in Juypter's nbviewer or Colab.</li>
    <li>Personal Notes: Similar to the MNIST dataset of images of handwritten digits, this variation uses the Fashion MNIST dataset of digitized images of clothing. Like MNIST, there are 60K training images and 10K testing images each with 28x28=728 pixels. A copy of a complete run is provided in the files of this repository (fashion classification.ipynb) </li>
     </ul>
     </li>
<br>    
    <li>Source: <a href=https://machinelearningmastery.com/tensorflow-tutorial-deep-learning-with-tf-keras/">TensorFlow 2 Tutorial: Get Started in Deep Learning With tf.keras. Jason Brownlee, 2019</a>
    <ul>
    <li>Code: the code is provided in the article.  I used that code to produce an iPython notebook in Colab (see tf_2_tfKeras_Tutorial.ipynb) in the files with this repository.</li>
    <li>Personal Notes: Covers a wide variety of deep learning algorithms utilizing TensorFlow 2 and tf.keras.  Examples including: Ionosphere binary classification dataset to predicting whether a structure is in the atmosphere or not given radar returns; the Iris multiclass classification dataset for predicting the species of an iris flower given measures of the flower; the Boston Housing regression dataset for predicting housing values (a continuous variable) based on properities of the house and neighborhood; the MNIST dataset of digitized images of handwritten numbers between 0-9 and classified using Convolutional Neural Nets; the Car Sales dataset used to demonstrate LSTM RNN for univariate time series forecasting.</li>
     </ul>
     </li>
<br>    
    <li>Source: Human Activity Recognition using Accelerometers and Gyroscopes</a>
    <ul>
    <li>Code: An iPython notebook with the same name is contained in this repository. Additionally, a link is provided below for running the notebook </li>
    <li>Personal Notes: Utilizes human movement/activity data from the <a href="https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones">UCI HAR database</a> to develop a classification model aimed a recognizing a person's activity (walking, standing, sitting, etc.) based on measurements produced by the accelerometer and gyroscope in a Samsung smartphone. Here, the measures were generated in a controlled experiment by 30 subjects between the ages of 19-48 performing one of 6 standard activities (1-WALKING, 2-WALKING_UPSTAIRS, 3=WALKING_DOWNSTAIRS, 4-SITTING, 5-STANDING, 6-LAYING). Each subject wore a waist-mounted smartphone (Samsung Galaxy S II) with an embedded accelerometer and gyroscope that captured 3-axial linear acceleration and 3-axial angular velocity measures at a constant rate of 50Hz (i.e. 50 data points per second). The volunteers were video-recorded during their performances. The recordings were used to label the activities manually. Together the recordings and labeling process resulted in a dataset containing 7352 rows. The elements used in creating the dataset are provided in this repository in a folder titled 'data'.

In this particular analysis only one classification model -- Random Forest Classification -- was used to examine the dataset.  To perform the analysis the dataset was partitioned into 2 sets -- one containing 70% of the cases used for training and another containing 30% to be used for testing. Each set contains 561 features derived from the linear acceleration and angular velocity measures. Each row of the dataset contains the values for the 561 features generated by a single activity performed by a specific subject during a very short time period. When you examine the data you'll see that the data came from 21 out of the 30 subjects with each subject performing 1600 activities split close to evenly among the 6 labeled activities. 

In the end, the RFC proves to be very accurate and offers the ability to determine which of the features were key to generating the classification. See: https://nbviewer.jupyter.org/github/daveking63/Jupyter-iPython-Notebooks-Deep-Learning-Notes/blob/master/human_activity_recognition_using_accelerometers_and_gyroscopes.ipynb</li>.
     </ul>
     </li>
</ul>
