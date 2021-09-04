## Too Good to be True | py-truth 
![This is an image](https://www.internetmatters.org/wp-content/uploads/2020/10/learn-about-fake-news-600x315.png) 

(The weights of our best model can be found here: https://drive.google.com/file/d/14UtTy0A6z-ZlfHP6nN_TVQVYifeUchaG/view?usp=sharing)

This project aims at detecting fake and real news using machine learning algorithms and techniques

#### Vision & Goals
____________________________________________________________
In recent years, due to the booming development of online social networks and online media in general, fake news for various commercial and political purposes has been appearing in large numbers and has been spread all over in the online world. So, we want to build machine learning algorithms that can detect fake news.  

#### Data Collection 
____________________________________________________________
The dataset was acquired by [Kaggle]( https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset ) 

#### Data Processing 
____________________________________________________________
On the first phase we [explore](https://github.com/chriskal96/fake-news/blob/main/1_eda.ipynb) and [clean](https://github.com/chriskal96/fake-news/blob/main/2_text_pre_processing.ipynb ) our data. We have balanced data, which is very important for our models. 

#### Algorithms, NLP architectures  
____________________________________________________________
We use many algorithms in order to meet our business goals. 
* [Logistic Regression](https://github.com/chriskal96/fake-news/blob/main/3_Logistic_Regression.ipynb) 
* [Feed Forward Neural Network (NN)](https://github.com/chriskal96/fake-news/blob/main/4_Feed_Forward_NN.ipynb )
* [Recurrent NN](https://github.com/chriskal96/fake-news/blob/main/5_Recurrent_NN.ipynb) 
* [BERT] 

#### Results
____________________________________________________________
As we have evaluate all the models, we conclude that the best model is the Feed Forward NN  with accuracy **above 98% for both training and validation** and very small values for the loss function.
(The weights of our best model can be found [here](https://drive.google.com/file/d/14UtTy0A6z-ZlfHP6nN_TVQVYifeUchaG/view?usp=sharing)) 

#### Conclusion 
____________________________________________________________
Most of our models have very high accuracy not only because of the pre-processing but also because of the nature of the data. So, we use [Dummy Classifier](https://github.com/chriskal96/fake-news/blob/main/7_Dummy_Classifier.ipynb) which result in 51% accuracy and that means that our results are far better than those chosen with a not clever way.

#### Authors
____________________________________________________________
<a href="https://github.com/konstantinagewrg">Konstantina Georgiopoulou</a><br/>
<a href="https://github.com/antheodorou">Anastasios Theodorou</a><br/>
<a href="https://github.com/chriskal96">Christos Kallaras</a><br/>
Stavros Kasiaris
