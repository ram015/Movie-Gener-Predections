# Movie-Gener-Predections
My Goal for this experement is to develop a predictive model that can predict whether or not a movie is a Drama. In order to do I would need to use the textual features of the movie stories and creat your predictive models. There are totally three different files in this project.

movie_story_student_file.csv: This file contains the movie stories that should be used by students for model development.
movie_story_evaluation_file.csv: This should be used only for the evalution of the models
movies.csv: This file contain the movie genres.


Step 1: Explore all files to become familiar with the dataset
Step 2: There are 20,000 movies in movie_story_student_file.csvfile. Use the movies.csv file to determine whether a movie is Drama or not. The final output of this step should be development of a dataframe file that contains three columns: 1) movieId, 2) story, 3) DramaGenre. The value for the third column should be in a binary format. If the movie is drama the value should be 1, otherwise 0. Name the new file as main_dataset.
Step 3: If you want to just have one train and one test set, then split the main_dataset to train and test sets. Otherwise you can use cross validation methods.
Step 4: Use your supervised learning and text analysis knowledge to develope different predictive models (i.e. logestic regression, random forest, ...). Test the performance of your models in terms of accuracy, precision, recall, and F1 scores.
Step 5: Choose one of your best models (only one). Then use the full data available in main dataset to train that model.
Step 6: Prepare data in movie_story_evaluation_file.csv for prediction. You need to perform the exact same steps that you have done in Step 2 to prepare this new dataset. Name the new dataset as evaluation_dataset.
Step 7: Use your selected model in Step 5 to predict whether or not movies in evaluation_dataset are Drama movies.
Step 8: Report the final accuracy, precision, recall and F1 score.
