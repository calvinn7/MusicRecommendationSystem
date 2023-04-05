# MusicRecommendationSystem
Music Recommendation System Using Ruler-Based Approach
This is a music recommendation system created as part of an introduction to data science course. The system uses a content-based filtering approach to recommend music based on user interests and popularity.

Project Objectives
The main objectives of this project are to:

Create a machine learning model that can recommend relevant music to users
Provide a platform that suits listeners' profile in terms of music universe, content popularity, familiarity, new releases, appropriation cycle, diversity of genres, surprise, and continuation of past exploration
Enhance user experiences by finding top matches that relate the best for a particular music
Increase user loyalty and boost the popularity of the music recommendation system

Dataset
The dataset used in this project has undergone data preprocessing to ensure its suitability for the recommendation system.
https://www.kaggle.com/datasets/leonardopena/top-spotify-songs-from-20102019-by-year

Deployment of Data Products
The music recommendation system has been deployed as a web-based application using the Shiny R package. The system includes a UI with several tabs, input fields for selecting songs, and output displays for recommended songs and data visualization.

Functionality
The system includes the following tabs:

Main: allows users to select songs, display recommended songs generated by the model, and display top 20 popular songs from the dataset in the form of a table and bubble chart.
Info: includes two graphs - a bar chart to show the popularity of different genres and a word cloud graph to show the most frequent singers in the dataset.
Dataset: shows the dataset used in the music recommendation system and allows users to search for specific singers, songs, or genres.
About: includes general information about the application, the technique used to recommend songs, and some frequently asked questions.
Sample Output
After selecting 5 songs from the 20 randomly generated songs and clicking the “submit” button, the system will display a list of recommended songs.

Issues and Solutions
The system may encounter some issues, such as uninteresting sample songs, duplicate song selections, or incomplete recommendations. To address these issues, we have implemented solutions such as shuffling the sample songs, displaying warning messages, filtering out selected songs, and updating user selections.

Conclusion
The music recommendation system is a useful tool for enhancing user experiences and increasing user loyalty. With its content-based filtering approach and user-friendly interface, it provides an effective platform for recommending relevant music to users.

Link to website
https://calvinjmy993.shinyapps.io/MusicRecommendationSystem/


