# **Exploratory Data Analysis on Hollywood movies**

This is the repository that contains my analysis of the 1000 Hollywood movies.
The python notebook introduces the problem statement and runs throgh different scenarios of analyzing the data to generate insights.

Here is the summary of the exploratory data analysis:
1. Introduction  <br>
2. Problem Statement  <br>
3. Installing & Importing Libraries  <br>
  3.1. Installing Libraries <br>
  3.2. Importing Libraries  <br>
4. Data Acquisition & Description  <br>
  4.1 About the Data  <br>
  4.2 Data Import  <br>
  4.3 Data View  <br>
5. Data Pre-Profiling  <br>
  5.1 Data Description  <br>
  5.2 Data Information  <br>
  5.3 Data Unique Value Analysis  <br>
  5.4 Pandas Profiling Report  <br>
6. Data Pre-Processing  <br>
  6.1 Common Functions  <br>
  6.2 Existing columns changes  <br>
  6.3 Data type correction  <br>
  6.4 Handling missing data  <br>
  6.5 Revenue = 0?  <br>
  6.6 Handling outliers  <br>
  6.7 New columns addition - Feature Engineering  <br>
  6.8 Duplicate Analysis  <br>
7. Data Post-Profiling  <br>
  7.1 Data Description  <br>
  7.2 Data Information  <br>
  7.3 Pandas Profiling Report  <br>
8. Exploratory Data Analysis  <br>
  8.1 What is the correlation between Revenue, Runtime, Rating, Votes, Blockbuster and Metascore? <br>
  8.2 Year-wise Analysis  <br>
  8.2.1 What is the distribution of movies across years by number of blockbusters, length, quality? <br>
  8.2.2 What is the trend of revenue earned over the years? <br>
  8.2.3 What is the trend of average movie runtime over the years? <br>
  8.3 What is the relationship between movie quality, movie length, critic's scores and number of votes with revenue? <br>
  8.4 Runtime Analysis  <br>
  8.4.1 What is the runtime range where average revenue of movies is high? <br>
  8.4.2 How does the movie runtime affect rating? <br>
  8.4.3 How does the movie runtime affect votes and critic's score? <br>
  8.4.4 Which runtime range gives more blockbusters than the others? <br>
  8.5 Genre Analysis  <br>
  8.5.1 Which are the top 10 genres that make the highest revenue per movie(on average)? <br>
  8.5.2 Which are the top 10 genre that make the maximum number of blockbuster movies(sorted by percentage)? <br>
  8.5.3 Which are the top 10 genres based on average rating and average critic's score? <br>
  8.5.4 Which are the genres that are common in top 10 list of revenue, rating and critic's score? <br>
  8.5.5 Which genre combinations make most revenue per movie? <br>
  8.6 Actor Analysis  <br>
  8.6.1 Who are the top 10 actors that make the highest revenue per movie(on average)? <br>
  8.6.2 Who are the top 10 actors that make the maximum number of blockbuster movies(sorted by percentage)? <br>
  8.6.3 Who are the top 10 actors based on average rating and average critic's score? <br>
  8.6.4 Who are the actors that are common in top 10 list of revenue, rating and critic's score? <br>
  8.6.5 Which genres(top 5 highest revenue) do the top 10 actors perform in? <br>
  8.7 Director Analysis  <br>
  8.7.1 Who are the top 10 directors that make the highest revenue per movie(on average)? <br>
  8.7.2 Who are the top 10 directors that makes the maximum number of blockbuster movies(sorted by percentage)? <br>
  8.7.3 Who are the top 10 directors based on average rating and average critic's score? <br>
  8.7.4 Who are the directors that are common in the top 10 list of revenue, rating and critic's score? <br>
  8.7.5 Which genres(top 5 highest revenue) do the top 10 directors direct in? <br>
  8.7.6 Who are the actors(from highest revenue) that the top 10 highest revenue directors have worked with along with genre? <br>
  8.8 Director-Actor-Genre Analysis  <br>
  8.8.1 Who are the highest revenue actors that the top 10 highest revenue directors have worked with along with genres? <br>
  8.8.2 Who are the top rated actors that the top rated directors have worked with along with genres? <br>
9. Summarization  <br>
  9.1 Assumptions  <br>
  9.2 Conclusion  <br>
  9.3 Actionable Insights <br>
