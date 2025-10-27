Movie Recommendation System Using Sentiment Analysis From Microblogging Data
In this paper author is using social media Microblogging text to recommend movies to users by identifying sentiments from text. All existing recommendation techniques were using either content or collaborative filtering to recommend movies and this technique is not reliable when dataset contains few number of ratings or no ratings for some movies and this will raise cold (when sufficient data is not available for recommendation) problem. Both techniques require priori ratings data availability and if data not available then this technique will not work.
In propose paper author is adding sentiments based recommendation plus content and collaborative filtering where one model will be created with sentiment and other model will be created with content and collaborative filters and then application will scan both model to recommend movies to user
In propose work author has used MOVIELENS advance version dataset called ‘Movie Tweetings’ which contains movie details and movie tweets from users. So we used movie details to build content and collaborative model and we will used tweets to build sentiment model. To identify sentiments from tweets author using VADER sentiment API.
Below is the dataset screen shots used to implement this project and entire data available inside ‘Dataset’ folder
 
You can open and view content of each file
SCREEN SHOTS
To run project double click on ‘run.bat’ file to get below screen
 
In above screen click on ‘Upload Movie Tweetings Dataset’ button to load dataset
 
In above screen selecting and uploading entire “Dataset” folder and then click on ‘Select Folder” button to load dataset and to get below screen
 
In above screen dataset loaded and now click on ‘Read & Preprocess Dataset’ button to read and clean data from special symbols available in movie names   
 
In above screen application read data from tweets dataset, movies and rating dataset and now click on ‘Build Collaborative Filtering Model’ button to build model
 
In above screen collaborative matrix is created and now click on ‘Build Content Based Model’ button to build content model
 
In above screen content matrix model is generated with ratings and movie details and now click on ‘Build Sentiment Model” button to build sentiment object
 
In above screen sentiment model generated and now click on ‘Movie Recommendation using All Models” button to enter desire movie details and then application will recommend movies using all models
 
In above screen I entered details like I want movie with action, comedy and title must contains word like fury and if dataset contains actor details then we can give actor names also but this dataset not contains actor or director details. Now click ‘OK’ button to get below result
 
In above screen we are recommending some movies and for each movie we are calculating Content filter, collaborative filter ratings and sentiment and by seeing this values user may select best movie for himself. Similarly you can give any query on movies then application will suggest top movies based on content, sentiment and collaborative. Now click on ‘Top 10 Movie Sentiment Graph’ button to get sentiments count for all recommended movies
 
In above graph x-axis represents sentiment type and y-axis represents count of recommended movies and in above graph nearly 30 movies recommended and most of them falls in positive sentiment. 
