# Investigating-Netflix-Movies

# Overview/Introduction

Netflix, which started as a DVD rental service in 1997, has grown into one of the largest entertainment and media companies in the world. With a vast library of movies and TV shows, Netflix provides a rich dataset for exploratory data analysis (EDA). This project focuses on movies released in the 1990s, a decade known for its nostalgic and iconic films. The goal is to analyze Netflix data to better understand trends in movie genres, durations, and other characteristics during this period.

# Objectives

1. Analyze movies released in the 1990s available on Netflix.
2. Explore trends in movie durations and genres.
3. Identify the number of short action movies (less than 90 minutes) released in the 1990s.
4. Provide insights into the types of movies that were popular during this decade.

# Data Source

The dataset, netflix_data.csv, contains the following columns:
  - show_id: Unique ID for the show.
  - type: Type of show (Movie or TV Show).
  - title: Title of the show.
  - director: Director of the show.
  - cast: Cast members of the show.
  - country: Country of origin.
  - date_added: Date the show was added to Netflix.
  - release_year: Year the show was released.
  - duration: Duration of the show in minutes.
  - description: Description of the show.
  - genre: Genre of the show.

# Tools Used

- Python Libraries: Pandas, Matplotlib
- Data Analysis: Filtering, grouping, and summarizing data.
- Data Visualization: Histograms for analyzing movie durations.

#Insights

1. Movie Durations:
    - The majority of movies from the 1990s have durations between 90 and 120 minutes.
    - A smaller number of movies are shorter than 90 minutes or longer than 120 minutes.
  
    ![d6](https://github.com/user-attachments/assets/deae9ca9-7b5a-4cf1-9c01-9630401d72cf)

2. Action Movies:
    - Only 7 action movies from the 1990s have durations shorter than 90 minutes.
    - Examples include EVANGELION: DEATH (TRUE) (69 minutes) and Hero (89 minutes).
3. Genre Trends:
    - Dramas and action movies were popular genres during the 1990s.
    - Many movies from this decade are still available on Netflix, reflecting their enduring popularity.

# Recommendations

1. Content Creation:
    - Production companies focusing on nostalgic content should consider creating movies with durations between 90 and 120 minutes, as this aligns with audience expectations.
2. Genre Focus:
    - Given the popularity of dramas and action movies from the 1990s, modern productions could draw inspiration from these genres to appeal to nostalgic audiences.
3. Further Analysis:
    - Explore other genres (e.g., comedies, thrillers) from the 1990s to identify additional trends and opportunities for content creation.
4. Audience Engagement:
    - Highlight 1990s movies on Netflix through curated playlists or recommendations to engage viewers who enjoy nostalgic content.

# How to Use This Repository

1. Clone the repository.
2. Install the required Python libraries (pandas, matplotlib).
3. Run the Jupyter Notebook (Investigating Netflix Movies.ipynb) to reproduce the analysis.
4. Explore the dataset and modify the code to conduct further analysis or generate additional insights.
