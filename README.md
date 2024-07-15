
# EDA And Feature Engineering on Google PlayStore Data




![Logo](https://theleaker.com/wp-content/uploads/2019/01/google-play-store-2018-e1549038094948.jpg)
## Introduction
This repository contains an exploratory data analysis (EDA) and feature engineering performed on dataset "Google PlayStore".The dataset contains various attributes of mobile applications available on the platform.
## About Dataset 
The Dataset comprises the following features :

   App: The name of application.

   Category: The category under which the app falls.

   Rating: The rating of the application on the PlayStore.

   Reviews: The number of reviews the app has received.

   Size: The size of the app.

   Installs: The number of Installs of the app.

   Type: Whether the app is free or paid.

   Price: The price of the app(0 if it is paid).

   Content Rating: The appropriate target audience of the app.

   Genres: The genre under which the app falls.

   Last Updated: The date when the app was last updated.

   Current Ver: The current version of the application.

   Android Ver: The minimum android version required to run the app.




## Prerequisites
To run the notebook and scripts ,you need to have the following packages installed:

   * pandas

   * numpy

   * matplotlib

   * seaborn

   * jupyter
## Steps Involved
* Data Cleaning : The dataset requires cleaning before performing any analysis.The steps include:
   * Handling missing values.
   * Converting data types.
   * Parsing and standardizing fields(e.g.,Size,    Installs). 
* Feature Engineering : It involves creating new features from existing ones(e.g.,extract day,month and year feature )
* Exploratory Data Analysis : EDA involves examining the data to summarize its main characteristics ,often using visual methods.It includes:
    *  Histograms,scatter plot, count plots , pie charts and correlation heatmaps.
    * Identifying patterns and trends by examining the relationships between features(e.g., total Installs vs. year).
## Insights
The results of the EDA and feature engineering steps are presented in the respective notebook.Key Insights include:
   * Distribution of Categories and Genres.
   * Distribution of ratings , installs , reviewes and year etc.
   * Determine the trend between ratings vs. year.
   * Determine the positive and negative correlation between features.
## Contributing

Contributions are always welcome!If you have any suggestions and improvements , feel free to open an issue or create a pull request.




## License

This project is licensed under the MIT License.[MIT](https://choosealicense.com/licenses/mit/)


## Acknowledgements

 * The dataset was obtained from kaggle.
