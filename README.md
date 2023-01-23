<h1 align="center"> Book Recommendation System </h1>

![image](https://images.unsplash.com/photo-1670409702404-7bebbe0721cc?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2580&q=80)

<h3 align="center"> AlmaBetter Verfied Project - <a href="https://www.almabetter.com/"> AlmaBetter School </a> </h5>

<p>This model can recommend a book to a user on his/her preference in Python using the Colaborative Filtering.</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> 💾 Table of Content</h2>

  * Overview Dataset Information
  * Dataset Information
  * EDA and Feature Engineering
  * Model
  * Result

This project is aimed at recommending a book based on user preference.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)


<h2> 🌐 Overview</h2>

In a very general way, recommendation systems are algorithms which are aimed at suggesting relevant items to users such as movies, books or other products. Recommender systems are really critical in some industries as they can generate a huge amount of income when they are efficient or also be a way to stand out significantly from competitors. The main objective of this project is to create a book recommendation system for users.

Technology and tools wise this project covers,

1. Python

2. Numpy and Pandas for data cleaning

3. Data visualization

4. Sklearn for model building

5. Jupiter Notebook
 

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> 📖 Dataset Information</h2>
3 different datasets are used to get finally dataset, these 3 datasets are 

1. 'Books' - it has the required data about books.
<p align="left" width="100%">
    <img width="100%" src="https://user-images.githubusercontent.com/90998859/214016283-0f7492fd-1bdc-4318-bcea-440619e8cf74.png">
</p>
2. 'Ratings' - it has the ratings of the books given by users.
<p align="left" width="100%">
    <img width="100%" src="https://user-images.githubusercontent.com/90998859/214017302-a97d8883-27da-43f0-bfec-9b8ca66253a8.png">
</p>
3. 'Users' - it has the discription about the user
<p align="left" width="100%">
    <img width="100%" src="https://user-images.githubusercontent.com/90998859/214016763-030b33df-82ff-4b60-b2eb-2264ecdeeaa6.png">
</p>

The final dataset that is created with the help of above 3 datasets has the following 7 columns (features):

<p align="left" width="100%">
    <img width="100%" src="https://user-images.githubusercontent.com/90998859/214018736-37840006-ee2c-4a63-b833-6bbb35035927.png">
</p>

* user_id.

* ISBN

* rating

* title (book title)

* author

* year (year of publication)

* publisher

![--------------------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
<h2> 👷‍♂️ EDA and Feature Engineering</h2>

* Missing Values Imputation

* Graphical Representation of all Datasets
  
  It includes 'Joint Plot', 'Bar Graph', 'Line Chart', etc.
  
  <p align="center" width="100%">
    <img width="30%" src="https://user-images.githubusercontent.com/90998859/214028381-f2cbdb64-7331-463d-aced-dfcbe51b7f80.png">
    <img width="30%" src="https://user-images.githubusercontent.com/90998859/214028646-cade80c0-2280-44b9-94c6-c0916cc3c936.png">
    <img width="30%" src="https://user-images.githubusercontent.com/90998859/214028959-144a8a93-4f0e-445d-8629-e3deffc23e17.png">
</p>

* New Features are created based on existing ones

* Features with less utilization are removed

* All 3 datasets are merged into one dataset with important features to train

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
<h2> 💻 Model</h2>

The following steps are covered while training the clean dataset into the algorithm:

i. The final dataset has been converted into pivot table. 

ii. The pivot table has been transformed into Spars Matrix with "scipy" library

iii. The given spars matrix has been trained on 'NearestNeighbors' with ‘brute’ algorithm.

![image](https://user-images.githubusercontent.com/90998859/214027808-380aad52-b019-4813-af4c-0ca00fb80b00.png)



![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
<h2> 🎖️ Result</h2>

The trained model gives the books suggestions based on the searched book along with the distance of similarity. The book with the least distance has been ranked on the top and the model is assigned to provide the 5 books.

The model is provinding the similarity results based on the distance:
<p align="left" width="100%">
    <img width="100%" src="https://user-images.githubusercontent.com/90998859/214020035-c9b9141e-5681-4963-bb19-884a57c4fc39.png">
</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
<!-- CREDITS -->
<h2 id="credits"> :scroll: Credits</h2>

< Vikas Chaudhary > | Data Science Enthusiast

<p> <i> Contact me for Data Science Project Collaborations and Research</i></p>


[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](www.linkedin.com/in/chvikas/)
[![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/chvikas)
[![Medium Badge](https://img.shields.io/badge/Medium-1DA1F2?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@chvikas)


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :book: Technologies Used::</h2>

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://user-images.githubusercontent.com/32620288/139657460-40ef4562-76bd-43f5-bbca-47b6bd29863e.png" width=100>](https://numpy.org)    [<img target="_blank" src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ed/Pandas_logo.svg/450px-Pandas_logo.svg.png" width=150>](https://pandas.pydata.org)  [<img target="_blank" src="https://seaborn.pydata.org/_static/logo-wide-lightbg.svg" width=150>](https://seaborn.pydata.org) [<img target="_blank" src="https://matplotlib.org/_static/logo2_compressed.svg" width=170>](https://matplotlib.org)   [<img target="_blank" src="https://user-images.githubusercontent.com/32620288/137518674-f36c5ad3-3d64-4c7a-a07c-53f247750394.png" width=170>](https://colab.research.google.com/)

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

