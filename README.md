# deep-learning-challenge

Alphabet Soup Report

Overview: 
The nonproft Alphabet Soup wants a tool to be able to better predict whether a venture is likely to be successful or not. With our knowledge of machine learning and deep learning, we were tasked to create a neural network model. The model's goal was to predict a venture's success with at leat 75% accuracy.

Results: 
    - Data Preprocessing
        - The target of the model were all the columns other than the "IS_SUCCESSFUL" column in the dataset.
        - The features of the model was specifically the "IS_SUCCESSFUL" column within the dataset.
        - There were two variables or columns that were removed from the dataset, being the "EIN" and "NAME" columns. 
    
    - Compiling, Training, and Evaluating the Model
        - In my final optimaztion attempt I had 240 neurons, 4 layers with 3 of them being hidden layers, and 75 epochs. I chose this setup to ry and include as many params as possible and yet try to limit possible loss. 
        - I was not able to reach the target of 75% and instead only reached 73%.
        - Throughout my attempts to increase accuracy, I changed the amount of neurons, added more hidden layers, and changed the number of epochs.

Summary: 
Overall, my results from my attempts did not reach the target goal of 75% accuracy. My changes in my optimzation models were not effectivie in increasing my accuracy and if anything made the model run a bit slower. In the future I would add more hidden layers but limit the amount of neurons. I would do this as I believe anoher hidden layer or two would get me closer to the desired goal and I would limit neurons becuase effeciency is just as important as accuracy. 