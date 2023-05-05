# EDA-on-Netflix-Movies-and-TV-Shows

![Netflix](images/netflix.jpg "Netflix")

Netflix is a leading player in streaming media with over 200 million global subscribers. Its transformation from DVD rental service to media publisher through its Netflix Originals program has made it a dominant player in the industry.





# About the data

### Records:

1. SHOW-ID - Unique id of each show (not much of a use for us in this project)
2. TYPE - The category of a show, can be either a Movie or a TV Show
3. TITLE - Name of the show
4. DIRECTOR - Name of the director(s) of the show
5. CAST - Name of the show
6. COUNTRY - Name of countries the show is available to watch on Netflix
7. DATE ADDED - Date when the show was added on Netflix
8. RATING - Show rating on netflix
9. RELEASE YEAR - Release year of the show
10. DURATION - Time duration of the show
11. LISTED IN - Genre of the show



# Content
0. **ABOUT THE DATA**

1. **IMPORTING LIBRARIES**

2. **DATA DESCRIPTION AND DATA CLEANING**

    1. Import data

    2. Data types

    3. Missing values
    
        ![Missing](images/missing_values.jpg "Missing")
        
    4. Duplicates

3. **DATA ANALYSIS**

    1. How content is distributed ?  
        ![Content distribution](images/production_types.png "Content distribution")

    2. WHAT ARE THE COUNTRIES WITH HIGHEST NUMBER OF MOVIES & TV-SHOWS ?  
        ![missing values](images/countries_highest_movies_and_tv_shows.jpg "missing values")
    
    3. what is the content added in each year ?  
        ![Content added](images/content_added_in_each_year.jpg "Content added")

    4. what are the ratio of the genres ?  
        ![genres](images/netflix_production_types.jpg "genres")

4. **RECOMMENDATION SYSTEM**
        The output of the recommendation system shows the top 10 movies or TV shows that are most similar to the input title based on their similarity score calculated         using cosine similarity. Here are some insights you can gather from the output:
        
        1. Genre similarity: The recommended movies and TV shows may share the same or similar genre as the input title. For example, Ocean's Eleven and Head Count are both in the crime genre, while Girlfriend's Day and Frank & Lola are in the romance genre.
        
        2. Actor similarity: Some of the recommended movies and TV shows may feature the same actors or actresses as the input title. For example, Ocean's Eleven an The Trust both star Nicolas Cage.
        
        3. Theme or plot similarity: The recommended movies and TV shows may have similar themes or plots as the input title. For example, Fear and Loathing in Las Vegas and Girlfriend's Day both explore the theme of relationships and self-discovery.


6. **CONCLUSIONS AND INSIGHTS**
   
   1. The data shows that Netflix has been adding more movies and TV shows each year since 2011, with the highest number added in 2019. However, there was a decrease in content added in 2021, potentially due to the COVID-19 pandemic. This trend suggests that Netflix has been investing heavily in original content and expanding partnerships with content creators to meet the growing demand for streaming content.
   
   2. The year 2019 had the highest number of movies added to the platform, while 2020 had the highest number of TV shows added. This suggests that Netflix may have invested more heavily in creating and acquiring TV shows in 2020, while still adding a significant amount of movies in 2019. While 2019 had the highest number of movies added, the number of TV shows added that year was relatively low compared to 2020. This suggests that Netflix may have been focusing more on developing and releasing new original TV shows in 2020, rather than acquiring existing content. There is a significant drop in the number of movies and TV shows added in 2021 compared to the previous years. This could be due to the impact of the COVID-19 pandemic on content production and acquisition. It is interesting to note that some years, such as 2014 and 2015, had relatively low numbers of content added to the platform compared to other years. This could be due to factors such as changes in the overall strategy of Netflix, or difficulties in acquiring or producing content during those years. Overall, the data suggests that Netflix has been consistently adding new movies and TV shows to its platform over the years, with some years showing a higher number of content additions than others. The data could be further analyzed by looking at the specific genres or types of content added in each year to gain additional insights.
   
   3. The analysis of the provided data on the ratio of genres on Netflix suggests that the majority of the content is aimed at adults, with 46.7% of the content falling into this category. Teenagers are the second largest demographic group, with 29.8% of content aimed at this age range. The percentage of content aimed at kids and older kids is relatively small, with only 6.53% and 17% of content falling into these categories, respectively. The data suggests that Netflix may not be as focused on creating content for young children or older kids, but is still providing some content for these audiences. The data could be further analyzed by looking at the specific genres and themes of the content to gain additional insights into audience demographics and preferences.
