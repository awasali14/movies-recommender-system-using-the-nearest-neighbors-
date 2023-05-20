# Movies-recommender-system-using-the-nearest-neighbors-

### What was my motivation?

Our motivation behind this project was to analyze and gain insights from the MovieLens dataset. We were interested in exploring the movie ratings data and understanding patterns, trends, and relationships between users, movies, and ratings.

### Why did I build this project?

We built this project to explore the MovieLens dataset and demonstrate how MATLAB can be used for data analysis and visualization. By analyzing movie ratings, we aimed to provide useful information and insights to users, such as identifying popular movies, trends over time, and making personalized movie recommendations.

### What problem does it solve?

This project solves the problem of analyzing and extracting meaningful information from a large movie ratings dataset. It allows users to gain insights into the dataset, such as understanding user behavior, identifying highly rated movies, and making predictions for unrated movies using a nearest neighbor approach. The project provides a comprehensive analysis of the movie ratings data, enabling users to make informed decisions and recommendations.

### What did I learn?

Through this project, we learned several key aspects of data analysis and manipulation using MATLAB. We gained experience in working with tabular data, extracting information from text fields, creating logical variables, joining and merging tables, and performing statistical computations. Additionally, we learned about the nearest neighbor method for making predictions and the importance of considering data characteristics when selecting appropriate prediction strategies. Overall, this project enhanced our skills in data analysis, visualization, and understanding user preferences and behavior based on ratings data.

## Prerequisites

Before running the code, make sure you have MATLAB installed on your system.

## Getting Started

Clone the repository or download the code files.
Open MATLAB and navigate to the project directory.

## Data Preparation

The code retrieves the MovieLens dataset by downloading and extracting the movie-ratings.zip file from the MovieLens website.
It reads the movies.csv and ratings.csv files from the dataset.
The code processes the movies data by extracting the release year from the movie titles and creating logical variables for each genre.
It removes the original genre variable from the movies table.

## Data Analysis

The code performs various analyses on the ratings data.
It calculates the total number of ratings in the dataset.
It identifies the user with the most reviews and the number of unique user IDs in the dataset.
The code joins the ratings and movies tables to combine the movie information with the corresponding ratings.
It determines the number of unique movies in the ratings dataset and identifies the most reviewed movie.
The code calculates the mean rating for the original Star Wars trilogy and the Star Wars prequels.
It groups the ratings by year and plots the mean rating and the number of ratings over time.
The code calculates the mean absolute prediction error using the overall mean rating.
It predicts movie ratings using the nearest neighbor method and calculates the mean absolute error.
The code provides recommendations for movies to the user based on their nearest neighbors' ratings.

## Usage

Run the MATLAB code in the provided script.
The code will output various analyses and insights into the movie ratings dataset.

## Customization

You can customize the code by modifying the following parameters:

dataset: Specify the MovieLens dataset to use.

minInCommon: Set the minimum number of shared movies required for nearest neighbor prediction.

maxDist: Set the maximum distance for nearest neighbor search.

minRtgs: Set the minimum number of ratings required for nearest neighbor prediction.

## Contributing

Contributions to the project are welcome. If you find any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License.

## Acknowledgments

The code utilizes the MovieLens dataset available at MovieLens.
The MovieLens dataset is provided by GroupLens Research at the University of Minnesota.
