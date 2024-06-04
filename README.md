# Movie Recommendation System

This project aims to build a movie recommendation system using collaborative filtering techniques. The system suggests movies to users based on their preferences and the preferences of similar users.

## Project Overview

The movie recommendation system utilizes user ratings data to identify patterns and make personalized movie recommendations. It employs collaborative filtering algorithms to find similar users and recommend movies that those users have liked.

## Dataset

The dataset used in this project is the MovieLens dataset, which contains movie ratings from various users. The dataset includes information such as user IDs, movie IDs, ratings, and timestamps.

## Dependencies

To run the code in this project, you need to have the following dependencies installed:

- Python (version 3.6 or higher)
- pandas
- numpy
- scikit-learn
- matplotlib

You can install the required libraries using pip:

```
pip install pandas numpy scikit-learn matplotlib
```

## Usage

1. Clone the repository:

   ```
   git clone https://github.com/Mayur-vora/Movie-Recommendation-System.git
   ```

2. Navigate to the project directory:

   ```
   cd Movie-Recommendation-System
   ```

3. Open the Jupyter Notebook file `Movie Recommendation System.ipynb` in Jupyter Notebook or any compatible environment.

4. Run the notebook cells in sequential order to execute the code and build the movie recommendation system.

## Methodology

The movie recommendation system follows these steps:

1. Data Preprocessing:
   - Load the dataset and perform necessary data cleaning and formatting.
   - Split the dataset into training and testing sets.

2. Collaborative Filtering:
   - Implement user-based collaborative filtering using the k-Nearest Neighbors (kNN) algorithm.
   - Compute user similarity based on their movie ratings.
   - Predict movie ratings for a given user based on the ratings of similar users.

3. Evaluation:
   - Use the testing set to evaluate the performance of the recommendation system.
   - Calculate metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE) to assess the accuracy of the recommendations.

4. Recommendations:
   - Generate movie recommendations for a specific user based on their preferences and the trained model.
   - Display the top recommended movies along with their predicted ratings.

The code in the notebook provides step-by-step instructions and explanations for each stage of the recommendation system.

## Results

The movie recommendation system achieves reasonable accuracy in predicting movie ratings and generating personalized recommendations for users. The evaluation metrics, such as MAE and RMSE, provide insights into the performance of the system.

For detailed results and analysis, please refer to the Jupyter Notebook.

## Future Enhancements

There are several potential improvements and extensions to this movie recommendation system:

- Incorporate additional features such as movie genres, cast, and director information to enhance the recommendation quality.
- Experiment with different collaborative filtering algorithms, such as matrix factorization or deep learning-based approaches.
- Implement a user interface to allow users to interact with the recommendation system and provide feedback on the recommended movies.
- Explore hybrid recommendation approaches that combine collaborative filtering with content-based filtering.

## Contributing

Contributions to this project are welcome. If you have any suggestions, improvements, or additional features to propose, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
