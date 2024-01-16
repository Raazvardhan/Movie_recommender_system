# Movie Recommender System using TMDB 5000 Movie Dataset
![image](https://github.com/Raazvardhan/Random-User-Generator/assets/139915269/29a90c82-a128-4dce-8008-569c45709238)

## Overview

This Movie Recommender System is a Python application that uses the TMDB 5000 Movie Dataset to recommend similar movies based on user input. The system employs a content-based recommendation approach, analyzing movie features such as genres, keywords, and cast to find similarities and provide relevant recommendations.

## Features

- **Input Movie Name:** Users can input the name of a movie they like.
- **Top 5 Similar Movies:** The system will output the top 5 movies that are most similar to the input movie based on various features.

## Dataset

The TMDB 5000 Movie Dataset is used as the source of movie information. It contains data on a wide range of movies, including details such as title, genres, keywords, cast, and more.

Dataset Source: [TMDB 5000 Movie Dataset](https://www.kaggle.com/tmdb/tmdb-movie-metadata)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/MovieRecommenderSystem.git
   ```

2. Navigate to the project directory:

   ```bash
   cd MovieRecommenderSystem
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Ensure you have Python installed on your machine.

2. Run the application:

   ```bash
   python movie_recommender.py
   ```

3. Enter the name of a movie when prompted.

4. Receive the top 5 recommendations based on the input movie.

## Example

```
Enter the name of a movie: Inception
Top 5 Recommended Movies:
1. Interstellar
2. The Dark Knight
3. The Prestige
4. Shutter Island
5. Memento
```

## Notes

- The recommendations are based on content features such as genres, keywords, and cast.
- The system may not provide accurate recommendations for very obscure or unique movies not well-represented in the dataset.

Feel free to explore and modify the code to enhance the system or adapt it to your specific requirements. If you encounter any issues or have suggestions for improvement, please open an issue on the GitHub repository.
