# Sergi Portolio
Data Science &amp; Data Analytics


# [Data Extraction and Filtering from Google Sheets to Google Slides with AI](https://github.com/SergiDataAnalyst/filtering_data_with_ai/blob/main/ai_filtering.ipynb)
Extracting data from any Google Sheets file, performing filtering using AI, and generating customized Google Slides based on the filtered data. 
* Data Extraction from Google Sheets: The project retrieves data from Google Sheets using the Google Sheets API. It converts the data into a pandas DataFrame, allowing for easy manipulation and analysis. Missing or null data is deleted informing about missing values.
* Data Filtering using AI: The user inputs a desired prompt which is automatically translated to a pandas df query to filter the data. 
* Google Slides Creation and Data Writing: The project utilizes the Google Slides API to create customized slides for each filtered data subset. Copies of a source template are generated, and placeholders within the slides are replaced with the filtered data. The resulting slides are shared with the specified email address.
* Streamlit App to test this feature 


<p align="center">
  <img src="https://raw.githubusercontent.com/SergiDataAnalyst/Prison-Escape-Data-Analysis-/main/diagram.png" alt="Sublime's custom image"/>
</p>

# [Using Deep Learning for Superhero Classification](https://github.com/SergiDataAnalyst/image_classification_superhero/blob/main/image_classification_superhero.ipynb)
This code uses CNN models to perform an image classification task where the goal is to classify images of two different superhero characters (Deadpool and Hulk). Some key aspects of this project are:

* Data Loading: The code loads the images from two different subfolders in the 'data' directory, using the os and cv2 libraries. It also removes any unwanted image formats using the imghdr library.
* Data Preprocessing: The code resizes the images to a standard size (256x256) and scales the pixel values to be between 0 and 1 using the tf.keras.utils.image_dataset_from_directory() function. The images are also split into training, validation, and test sets.
* Modelling: The code builds a convolutional neural network (CNN) model using the tf.keras.models.Sequential() class. The model consists of several layers, including convolutional, max-pooling, and fully connected layers. The model is compiled using the adam optimizer and the categorical_crossentropy loss function.
* Training: The model is trained using the fit() method, which takes in the training and validation data sets. The code also uses several callbacks, such as the EarlyStopping and ModelCheckpoint callbacks to monitor the training process and save the best model.
* Evaluation: The model is evaluated using the evaluate() method, which takes in the test data set. The code also uses the sklearn.metrics.classification_report() function to generate a classification report, which includes various metrics such as precision, recall, and F1-score for each class.

<p align="center">
  <img src="https://raw.githubusercontent.com/SergiDataAnalyst/Prison-Escape-Data-Analysis-/main/840_560.jpeg" alt="Sublime's custom image"/>
</p>

# [Using Machine Learning to predict energy requirements on a milling machine](https://github.com/SergiDataAnalyst/energy_prediction_ML/blob/main/Energy_prediction.ipynb)
To mitigate the effects of climate change and protect the environment, Germany set a goal to increase its share of renewable energy in the power generation to 80% by 2050 (Bundesministerium für Wirtschaft und Energie 2017). However, since renewable energy generation from sources such as wind or sun is highly volatile, accurate forecasts of non-controllable electrical load are necessary to flexibly manage and achieve demand-supply balance. Electricity is currently the most important energy vector in the domestic sector and industry. Unlike fuels, electricity is hard and expensive to store. This creates the need of precise coupling between generation and demand. For these reasons, energy consumption forecasting is vital. The time scale for forecasting depends on who is interested in such prediction. 
* Analyzing and cleaning the data
* Splitting and training of the data set
* Deploying three machine learning models
* Evaluating and comparing each model
* Using the best model to predict inputs

<p align="center">
  <img src="https://raw.githubusercontent.com/SergiDataAnalyst/Prison-Escape-Data-Analysis-/main/milling.jpg" alt="Sublime's custom image"/>
</p>

# [Using MLE to estimate Weibull Distribution Parameters for Wind Energy Optimization](https://github.com/SergiDataAnalyst/weibull_wind_distribution/blob/main/wind_weibull.ipynb) 
The generation of electricity from wind energy has become increasingly important as the world moves towards sustainable energy sources. The accuracy of energy predictions and the optimization of energy production is crucial for minimizing economic losses and improving the coordination of smart grids. In this project, the use of Maximum Likelihood Estimation (MLE) methods is applied to find the Weibull distribution parameters of two different wind distributions in different locations. The Weibull distribution is widely used in various fields, including reliability engineering, to model both accelerating and decelerating failure rates and to accurately fit a wide range of data sets. In the context of wind energy, Weibull parameters play a crucial role in the selection of wind turbine models, as well as in the design of wind farms. The project aims to accurately estimate these parameters and classify the different wind profiles as on-shore or off-shore configurations. The focus is on horizontal axis wind turbines (HAWT), which are the most commonly used wind turbines and capable of generating a significant amount of electricity.

* Used 2 wind datasets recordings
* Using MLE to calculate the Weibull parameters
* Using OOP for data visualization
* Graphing the power curve of the turbines

<p align="center">
  <img src="https://raw.githubusercontent.com/SergiDataAnalyst/Prison-Escape-Data-Analysis-/main/wind_turbine.jpg" alt="Sublime's custom image"/>
</p>

# [Scrapping Reddit data and using ChatGPT to write engaging post titles](https://github.com/SergiDataAnalyst/Reddit_scrapping_project/blob/main/Reddit_Scrapping_Project.ipynb) 
For this project I built a bot to browse and extract data from any subreddit. The bot can access data from subreddit posts labeled as `New`, `Trending` or `Top`. The useful information gathered for each post is, the complete title, number of upvotes, number of comments and the date and time. This project aims to showcase the importance of choosing keywords or emojis to give a better engagement. The reason behind choosing Reddit is because during the past years it has become a relevant source for statistical information collection for surveys since it offers a notorious widespread representation of nowadays society spectrum of opinion.

* Used the Python Reddit API Wrapper tool to generate a scrapping data bot
* Data gathering from desired subreddit(s) into `.csv` files stored locally to later import them as a DataFrame
* Cleaning the data stored in the DataFrame containing hundreds of posts information
* Organizing and classifying the DataFrame
* Creating dictionaries with the most relevant keywords and emojis
* Analyzing the impact of keywords
* Using the ChatGPT API

<p align="center">
  <img src="https://raw.githubusercontent.com/SergiDataAnalyst/Prison-Escape-Data-Analysis-/main/reddit.png" alt="Sublime's custom image"/>
</p>



# [Overlaying glottis images and accessing their metadata for a better diagnosis](https://github.com/SergiDataAnalyst/glottis/blob/main/glottis.ipynb) 
A quick medical diagnosis can help save lives! Once a patient seeks health care, there is an iterative process of information gathering, information integration and interpretation, and determining a working diagnosis. Performing a clinical history and interview, conducting a physical exam, performing diagnostic testing, and referring or consulting with other clinicians are all ways of accumulating information that may be relevant to understanding a patient's health problem. The information-gathering approaches can be employed at different times, and diagnostic information can be obtained in different orders. The continuous process of information gathering, integration, and interpretation involves hypothesis generation and updating prior probabilities as more information is learned. 
Of major importance in the diagnostic process is the element of time. Most diseases evolve over time, and there can be a delay between the onset of disease and the onset of a patient's symptoms; time can also elapse before a patient's symptoms are recognized as a specific diagnosis. Sometimes, image diagnosis can become a rather long wait, this can be caused by a bottleneck in the health care system. Machine Learning algorithms can help speed up this process and potentially save lifes.
* Created a tool that imports and opens images and accesses their metadata files
* Overlaying of images and their segmented masks for a better first view
* Labeling the result overlayed images with information stored in their metadata file
* Analyzing data from segmented mask images
* Developing a `Machile Learning` algorithm to examine and determine the diagnosis of a patient (pending)
* Training dataset of images (pending)


<p align="center">
  <img src="https://raw.githubusercontent.com/SergiDataAnalyst/Prison-Escape-Data-Analysis-/main/glottis.png" alt="Sublime's custom image"/>
</p>


# [Will it snow in Munich on Christmas Eve? ](https://github.com/SergiDataAnalyst/Predicting_snow_in_munich/blob/main/munich_weather.ipynb) 

As in many other scientific fields, the proliferation of tools like artificial intelligence and machine learning holds great promise for weather prediction. We have seen some of what’s possible in our research on applying machine learning to forecasts of high-impact weather. These tools open up new possibilities for better forecasts.
Artificial intelligence and machine learning can help with some of these challenges. Forecasters are using these tools in several ways now, including making predictions of high-impact weather that the models can’t provide.
* Importing historical data to a DataFrame from a .csv file
* Data visualization
* Data cleaning and classication
* Implementation of a linear regression machine learning model to work with the data
* Choosing of predictor variables
* Training of the DataFrame
* Studying of the overall impact of the different predictor variables


<p align="center">
  <img src="https://raw.githubusercontent.com/SergiDataAnalyst/Prison-Escape-Data-Analysis-/main/snowed.png" alt="Sublime's custom image"/>
</p>

# [Modifying the internal RGB values of a picture to alter the original output](https://github.com/SergiDataAnalyst/leaves/blob/main/Leaves.ipynb) 

As in many other scientific fields, the proliferation of tools like artificial intelligence and machine learning holds great promise for weather prediction. We have seen some of what’s possible in our research on applying machine learning to forecasts of high-impact weather. These tools open up new possibilities for better forecasts.
Artificial intelligence and machine learning can help with some of these challenges. Forecasters are using these tools in several ways now, including making predictions of high-impact weather that the models can’t provide. [^1]
* Importing historical data to a DataFrame from a .csv file
* Data visualization
* Data cleaning and classication
* Implementation of a linear regression machine learning model to work with the data
* Choosing of predictor variables
* Training of the DataFrame
* Studying of the overall impact of the different predictor variables


[^1]: [Source](https://www.johndcook.com/blog/2009/08/24/algorithms-convert-color-grayscale)

<p align="center">
  <img src="https://raw.githubusercontent.com/SergiDataAnalyst/Prison-Escape-Data-Analysis-/main/leaves.png" alt="Sublime's custom image"/>
</p>


# [Visualization of US census data](https://github.com/SergiDataAnalyst/US_census_2020/blob/main/US_census.ipynb) 

As in many other scientific fields, the proliferation of tools like artificial intelligence and machine learning holds great promise for weather prediction. We have seen some of what’s possible in our research on applying machine learning to forecasts of high-impact weather. These tools open up new possibilities for better forecasts.
Artificial intelligence and machine learning can help with some of these challenges. Forecasters are using these tools in several ways now, including making predictions of high-impact weather that the models can’t provide.
* Importing historical data to a DataFrame from a .csv file
* Data visualization
* Data cleaning and classication
* Implementation of a linear regression machine learning model to work with the data
* Choosing of predictor variables
* Training of the DataFrame
* Studying of the overall impact of the different predictor variables


<p align="center">
  <img src="https://raw.githubusercontent.com/SergiDataAnalyst/Prison-Escape-Data-Analysis-/main/census.png" alt="Sublime's custom image"/>
</p>
