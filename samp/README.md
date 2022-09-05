# Adaptive-Learning-IRT

* Diificulty_final.ipynb - A model to predict difficulty of the next question based on the paramenters - Time taken to answer, response, difficulty of the present question, concept is trained and tested with 5 questions. 
* IRT.ipynb - The responses and the difficulty of each question is read from a csv file and the abilities of 2 students are estimated
* txt_csv.ipynb - To convert txt file into csv file
* Concept_Difficulty.ipynb - To assign the difficulties and concepts for each question in the dataset (MCQ_Dataset.csv)
* assigning_difficulties.ipynb - For assigning the labels (difficulty of the next question) to the concepts_9.csv file
* Concept_9.csv - Datset of student responses for training the model  
* MCQ_Dataset.txt - Dataset of  MCQ Questions in a txt file
* MCQ_Dataset.csv - Dataset of  MCQ Questions in .csv format ( MCQ_Dataset.txt to MCQ_Dataset.csv using txt_csv.ipynb)
* MCQ_Dataset1.csv - Dataset of  MCQ Questions in .csv format after assigning the concept  and difficulty attributes using Concept_Difficulty.ipynb
